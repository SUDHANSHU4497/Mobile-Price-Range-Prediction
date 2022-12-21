
# Mobile Price Range Prediction (Classification)
1. Introduction
2. Problem Statement
3. data Desctiption
4. Conclusions

<p align="center">
  <img 
    width="750"
    height="400"
    src = "https://media4.giphy.com/media/5UtdtSHWnhjfG5Sz8N/giphy.gif?cid=6c09b952672fe95690f9418ee6eb304431fe89b86cd0129c&rid=giphy.gif&ct=g">
</p>

****

1. Introduction:

Price is the most important component in the marketing of any product and is often the definitive factor in its sale to a consumer. In a constantly evolving and volatile market, the price is often the factor that makes or breaks a product. Setting an optimal price before the release of a product is imperative for any company. A tool that gives the estimated price of a product after weighing in the features it provides can come in handy and can help the company in making an informed decision while setting the market price for a product.

2. Problem Statement

The main objective of this project is to build a predictive model, which predicts whether the price range of mobile phones available in the market on the basis of various mobile featrures. Mobile price ranges are as 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost). Therefore this is a multiclass classification problem.

3. Data Description:

 The dataset provides the information about following features of mobile phones.

    - Battery_power : Total energy a battery can store in one time measured in mAh
    - Blue : Has bluetooth or not
    - Clock_speed : speed at which microprocessor executes instructions
    - Dual_sim : Has dual sim support or not
    - Fc : Front Camera mega pixels
    - Four_g : Has 4G or not
    - Int_memory : Internal Memory in Gigabytes
    - M_dep : Mobile Depth in cm
    - Mobile_wt : Weight of mobile phone
    - N_cores : Number of cores of processor
    - Pc : Primary Camera mega pixels
    - Px_height : Pixel Resolution Height
    - Px_width : Pixel Resolution Width
    - Ram : Random Access Memory in Mega Bytes
    - Sc_h : Screen Height of mobile in cm
    - Sc_w : Screen Width of mobile in cm
    - Talk_time : longest time that a single battery charge will last when you are
    - Three_g : Has 3G or not
    - Touch_screen : Has touch screen or not
    - Wifi : Has wifi or not
    - Price_range : This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost). (DEPENDENT VARIABLE)
    - Total number of rows in data : 2000
    - Total number of columns : 21

4. Conclusions:

    * KNN with or without GridSearchCV show poor accuracy score as compare to other model.
    * SVC with GridSearchCV having train accuracy score is 0.984 and test accuracy score is 0.962 which is good performer.
    * GradientBoostingClassifier with GridSearchCV have test accuracy score is 0.992 and train accuracy score is 0.999, which is best among all the model. Hence we can deploy this model.


           
