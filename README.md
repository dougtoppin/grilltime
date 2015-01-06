grilltime
=========

Use AngularJS to help determine how much time remains in my propane tank.

A while back I realized that I was probably replacing the propane tank on our grill sooner than I needed to because I was not sure how much gas was still in it.
To calculate the remaining time all you need to do is know how much gas is in the tank and how fast your grill burns it (BTUs).
You have to weigh your tank to know how much remains in it so you need your bathroom scale.
I did a simple AngularJS html page and put it in an AWS S3 bucket if you want to try it.
It is not pretty but we are going to run our tank dry before carting it off to Home Depot next time.
There is no error checking in it so if you bring down the Internet then it's your fault.
If you want to see this running in an AWS static site take a look at [http://propanecalculator.dougtoppin.name/](http://propanecalculator.dougtoppin.name/)

