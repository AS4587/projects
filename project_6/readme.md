Project №6. Car Price Predict

Task.

    Predict car prices in test data where target is missing

Job.

    * Parse fresh data
    * Preprocessing of data which already exsist
    * EDA and feature engenering
    * Create models and find best parametrs
    * Try ansamble, blending, stacking

Conclusions.

    * Parsing:
    Code isn't working properly, but!
    Slow way sending by one car model in cycle manually I took out more than 3gb of info :)
    Problem was how I understand in parsing speed, cause sometimes cycle just didn't find some info in path, like 'KeyError: 'offers' '.
    When I was checking location manually there was info. I Just didn't have time to find where to put time.sleep()
    
    * Preprocessing of data which already exsist:
    Make everything what I can, think done well.
    
    * EDA and feature engenering:
    Didn't had enough time for deeper EDA analisys, and still have problem with visualization.
    Feature engenering didn't make at all, same reason
    
    * Create models and find best parametrs:
    Wasted hell lot of time on lazypredict() while understand that on kaggle it's dead variant, so run it in colab in the end.
    Used ExtraTreesRegressor, RandomForestRegressor, XGBRegressor, LGBMRegressor and BaggingRegressor (but lost metics from last one :(
    
    * Try ansamble, blending, stacking
    Had time only for stacking
    
What's next?

     * Want to continue
     * Try other models, make deeper EDA analisys and feature engenering
     * Try ansamble and blending
    
Big data take very, very much time!

Link

    Kaggle competition: https://www.kaggle.com/artdirector/credit-scoring

