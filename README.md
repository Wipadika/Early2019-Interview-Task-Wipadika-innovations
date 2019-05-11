# Early2019-Interview-Task-Wipadika-innovations

>We love people who like learning new things and thinking in the abstract. This task (hopefully) helps you discover and few new services and help illustrate some of your front end skills to us.

_Here's what you need to do:_

1) Clone this repository. **(DO NOT PUBLICLY FORK IT and DO NOT POST SOLUTIONS ONLINE)**

2) Choose one to perform the task

    a. ReactJs

    b. AngularJs

    c. React Native



3) Task: Make The Component as shown bellow

![](images/image1.png)


    1. The Main Text should get it from the bellow API
        URL: https://cdjmy3ceu7.execute-api.ap-south-1.amazonaws.com/dev/message

        Method: get

        Auth Headers => x-api-key : 1Vt72wYzBu2VGbdTVuC96YGB8mEMOkY6B2OqsSyb

        Response => 
        
                {
                    "statusCode": 200,
                    "status": "success",
                    "data": {
                        "message": "rpZpxwZGzezFuJrLCgrL"
                    }
                }

    2. The Main Text Should Refresh on Refresh button, or everytime window reloads

    3. create firebase functions using :

        a. firebase functions (cloud functions: rest)


    4. firebase function Logic : 

        a) on calling the function it shoud generate a string based on timestamp

        b) on refresh string should change

        c) All the strings has to be diffrent upon the timestamp

        d) Display the timestamp based generated string as the Second Text as shown in the Screenshot.

    5. on Refresh while getting the result show loader untill the value comes as shown bellow.

![](images/image2.png)

6) Once Done provide firebase commands to build, run , and deploy functions

7) ZIP the folder and send it to dev@wipadika.com

*All the Best*