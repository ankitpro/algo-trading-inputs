# **Table of contents**

* [Indicators by Category](#indicators-by-category)
    * [Candles](#candles-64)
    * [Cycles](#cycles-1)
    * [Momentum](#momentum-41)
    * [Overlap](#overlap-33)
    * [Performance](#performance-3)
    * [Statistics](#statistics-11)
    * [Trend](#trend-18)
    * [Utility](#utility-5)
    * [Volatility](#volatility-14)
    * [Volume](#volume-15)
<!--te-->


<br/>

# **Indicators** (_by Category_)
### **Candles** (64)
Patterns that are **not bold**, require TA-Lib to be installed: ```pip install TA-Lib```

* 2crows
* 3blackcrows
* 3inside
* 3linestrike
* 3outside
* 3starsinsouth
* 3whitesoldiers
* abandonedbaby
* advanceblock
* belthold
* breakaway
* closingmarubozu
* concealbabyswall
* counterattack
* darkcloudcover
* **doji**
* dojistar
* dragonflydoji
* engulfing
* eveningdojistar
* eveningstar
* gapsidesidewhite
* gravestonedoji
* hammer
* hangingman
* harami
* haramicross
* highwave
* hikkake
* hikkakemod
* homingpigeon
* identical3crows
* inneck
* **inside**
* invertedhammer
* kicking
* kickingbylength
* ladderbottom
* longleggeddoji
* longline
* marubozu
* matchinglow
* mathold
* morningdojistar
* morningstar
* onneck
* piercing
* rickshawman
* risefall3methods
* separatinglines
* shootingstar
* shortline
* spinningtop
* stalledpattern
* sticksandwich
* takuri
* tasukigap
* thrusting
* tristar
* unique3river
* upsidegap2crows
* xsidegap3methods
* _Heikin-Ashi_: **ha**
* _Z Score_: **cdl_z**
<br/>


### **Cycles** (1)
* _Even Better Sinewave_: **ebsw**

<br/>

### **Momentum** (41)
* _Awesome Oscillator_: **ao**
* _Absolute Price Oscillator_: **apo**
* _Bias_: **bias**
* _Balance of Power_: **bop**
* _BRAR_: **brar**
* _Commodity Channel Index_: **cci**
* _Chande Forecast Oscillator_: **cfo**
* _Center of Gravity_: **cg**
* _Chande Momentum Oscillator_: **cmo**
* _Coppock Curve_: **coppock**
* _Correlation Trend Indicator_: **cti**
    * A wrapper for ```ta.linreg(series, r=True)```
* _Directional Movement_: **dm**
* _Efficiency Ratio_: **er**
* _Elder Ray Index_: **eri**
* _Fisher Transform_: **fisher**
* _Inertia_: **inertia**
* _KDJ_: **kdj**
* _KST Oscillator_: **kst**
* _Moving Average Convergence Divergence_: **macd**
* _Momentum_: **mom**
* _Pretty Good Oscillator_: **pgo**
* _Percentage Price Oscillator_: **ppo**
* _Psychological Line_: **psl**
* _Percentage Volume Oscillator_: **pvo**
* _Quantitative Qualitative Estimation_: **qqe**
* _Rate of Change_: **roc**
* _Relative Strength Index_: **rsi**
* _Relative Strength Xtra_: **rsx**
* _Relative Vigor Index_: **rvgi**
* _Schaff Trend Cycle_: **stc**
* _Slope_: **slope**
* _SMI Ergodic_ **smi**
* _Squeeze_: **squeeze**
    * Default is John Carter's. Enable Lazybear's with ```lazybear=True```
* _Squeeze Pro_: **squeeze_pro**
* _Stochastic Oscillator_: **stoch**
* _Stochastic RSI_: **stochrsi**
* _TD Sequential_: **td_seq**
    * Excluded from ```df.ta.strategy()```.
* _Trix_: **trix**
* _True strength index_: **tsi**
* _Ultimate Oscillator_: **uo**
* _Williams %R_: **willr**

<br/>

### **Overlap** (33)

* _Arnaud Legoux Moving Average_: **alma**
* _Double Exponential Moving Average_: **dema**
* _Exponential Moving Average_: **ema**
* _Fibonacci's Weighted Moving Average_: **fwma**
* _Gann High-Low Activator_: **hilo**
* _High-Low Average_: **hl2**
* _High-Low-Close Average_: **hlc3**
    * Commonly known as 'Typical Price' in Technical Analysis literature
* _Hull Exponential Moving Average_: **hma**
* _Holt-Winter Moving Average_: **hwma**
* _Ichimoku Kink?? Hy??_: **ichimoku**
    * Returns two DataFrames. For more information: ```help(ta.ichimoku)```.
    * ```lookahead=False``` drops the Chikou Span Column to prevent potential data leak.
* _Jurik Moving Average_: **jma**
* _Kaufman's Adaptive Moving Average_: **kama**
* _Linear Regression_: **linreg**
* _McGinley Dynamic_: **mcgd**
* _Midpoint_: **midpoint**
* _Midprice_: **midprice**
* _Open-High-Low-Close Average_: **ohlc4**
* _Pascal's Weighted Moving Average_: **pwma**
* _WildeR's Moving Average_: **rma**
* _Sine Weighted Moving Average_: **sinwma**
* _Simple Moving Average_: **sma**
* _Ehler's Super Smoother Filter_: **ssf**
* _Supertrend_: **supertrend**
* _Symmetric Weighted Moving Average_: **swma**
* _T3 Moving Average_: **t3**
* _Triple Exponential Moving Average_: **tema**
* _Triangular Moving Average_: **trima**
* _Variable Index Dynamic Average_: **vidya**
* _Volume Weighted Average Price_: **vwap**
    * **Requires** the DataFrame index to be a DatetimeIndex
* _Volume Weighted Moving Average_: **vwma**
* _Weighted Closing Price_: **wcp**
* _Weighted Moving Average_: **wma**
* _Zero Lag Moving Average_: **zlma**

<br/>

### **Performance** (3)

Use parameter: cumulative=**True** for cumulative results.

* _Draw Down_: **drawdown**
* _Log Return_: **log_return**
* _Percent Return_: **percent_return**

<br/>

### **Statistics** (11)

* _Entropy_: **entropy**
* _Kurtosis_: **kurtosis**
* _Mean Absolute Deviation_: **mad**
* _Median_: **median**
* _Quantile_: **quantile**
* _Skew_: **skew**
* _Standard Deviation_: **stdev**
* _Think or Swim Standard Deviation All_: **tos_stdevall**
* _Variance_: **variance**
* _Z Score_: **zscore**

<br/>

### **Trend** (18)

* _Average Directional Movement Index_: **adx**
    * Also includes **dmp** and **dmn** in the resultant DataFrame.
* _Archer Moving Averages Trends_: **amat**
* _Aroon & Aroon Oscillator_: **aroon**
* _Choppiness Index_: **chop**
* _Chande Kroll Stop_: **cksp**
* _Decay_: **decay**
    * Formally: **linear_decay**
* _Decreasing_: **decreasing**
* _Detrended Price Oscillator_: **dpo**
    * Set ```lookahead=False``` to disable centering and remove potential data leak.
* _Increasing_: **increasing**
* _Long Run_: **long_run**
* _Parabolic Stop and Reverse_: **psar**
* _Q Stick_: **qstick**
* _Short Run_: **short_run**
* _Trend Signals_: **tsignals**
* _TTM Trend_: **ttm_trend**
* _Vertical Horizontal Filter_: **vhf**
* _Vortex_: **vortex**
* _Cross Signals_: **xsignals**


<br/>

### **Utility** (5)

* _Above_: **above**
* _Above Value_: **above_value**
* _Below_: **below**
* _Below Value_: **below_value**
* _Cross_: **cross**

<br/>

### **Volatility** (14)

* _Aberration_: **aberration**
* _Acceleration Bands_: **accbands**
* _Average True Range_: **atr**
* _Bollinger Bands_: **bbands**
* _Donchian Channel_: **donchian**
* _Holt-Winter Channel_: **hwc**
* _Keltner Channel_: **kc**
* _Mass Index_: **massi**
* _Normalized Average True Range_: **natr**
* _Price Distance_: **pdist**
* _Relative Volatility Index_: **rvi**
* _Elder's Thermometer_: **thermo**
* _True Range_: **true_range**
* _Ulcer Index_: **ui**

<br/>

### **Volume** (15)

* _Accumulation/Distribution Index_: **ad**
* _Accumulation/Distribution Oscillator_: **adosc**
* _Archer On-Balance Volume_: **aobv**
* _Chaikin Money Flow_: **cmf**
* _Elder's Force Index_: **efi**
* _Ease of Movement_: **eom**
* _Klinger Volume Oscillator_: **kvo**
* _Money Flow Index_: **mfi**
* _Negative Volume Index_: **nvi**
* _On-Balance Volume_: **obv**
* _Positive Volume Index_: **pvi**
* _Price-Volume_: **pvol**
* _Price Volume Rank_: **pvr**
* _Price Volume Trend_: **pvt**
* _Volume Profile_: **vp**
<br/>

