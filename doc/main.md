## Welcome

We aim to offer the best perimeter video surveillance in our category. We
detect perimeter breeches.

- $500 per camera per year
- [Value proposition](##vp)
- [Methodology](##method)
- [Team](##team)
- [Open business](##open)
- [Investing](##invest)

~investors
## Investors

To invest in Zen Surveillance, sign up for a one-year subscription and throw
us any other money our way.

~vp
## Value proposition

- We charge the highest price in our category
- We offer the best service in our category:
    - Near-zero [false-negative rate](##fn) 
    - Low [false-positive rate](##fp)
    - Low [latency](##latency)
- We make a 30% profit margin
    - How we calculate [cost](##cost)


~profit
## Profit margin

How we calculate costs:

* [Variables](##variables)
* [Guessing computer-vision accuracy](##guess)

~guess
## Guessing computer-vision accuracy

* CVFP = 50
* CVFN = 0.001

~variables
## Variables

* *CVFP* = the number of computer-vision false positives per day per camera
* *CVFN* = the proportion of internal red-team breeches that aren't detected by computer vision
* *MFP* = the average number of meditator's false positives per day per camera
* *MFN* = the proportion of internal red-team breeches that aren't detected by meditators

TODO: formalize






~fair
## A fair deal

* You give us 100 points in cash in exchange for 50 points of value
* We receive 100 points in cash, and keep 50 points in cash as profit
* Therefore, we're trading 50 points of value for 50 points in profit
* There's fifty-fifty deals all around


~redblue
## Red Team

We sell our blue team, and we sell our red team. Would you like us to evaluate
your security system? May we challenge you to evaluate each other via
mutual red-teaming.


* We give you [100 points of value](##100value) in exchange for 100 points in cash.

~100value


~fp
## False-positive rate

1 per month, assuming you're actively being red teamed.

~fn
## False-negative rate

1 per month, assuming you're actively being red teamed.

~latency
## Latency

95% of alarms go off within 2 seconds of a breech.

99% of alarms go off within 5 seconds.

~cost
## Cost

<a href="file/cost.pdf"><img src="img/cost.png" width="100%"></a>

~cv-accuracy
##  Accuracy of the CV system

* CVFP = the number of CV false positives per day per camera
* RT = response time = the average amount of time it takes for a meditator to assess a 
  CV false positive
* CVFP * RT = the amount of "feed time" required per camera per day
* Y = CVFP * RT / 7 = the amount of "screen time" required per camera per day

Let's say:

* CVFP = 10/day/camera
* RT = 20 seconds
* CVFP * RT = 200 seconds/day/camera = 0.002315 days/camera
* Y = CVFP * RT * 1/7 screen/cameras = 0.0003307 days/screen
* X = cameras/screen/day
* X * Y = 1 
* X = 3024 cameras/screen/day
* X / $1230.72/screen/day
* = $2.46/camera/day


0.002315 days/camera * 7 camera/screen

    0.002315 days
    ----------
    camera
--------------------
    7 cameras
    ---------
    screen

=

    0.002315 days       1 screen 
    ----------     *    ---
    cameras             7 cameras

~cost-meditators
## Cost of meditators

Each meditator:

* Works 30 hours/week (6 hours/day)
* Makes $30k/year plus benefits worth $10k/year
    * = $40k/year/meditator
    * = $25.64/hour/meditator
* To cover a screen for 24 hours requires two meditators
    * = 24 hours/day * 2 meditators * $25.64/hour/meditator = $1230.72/screen/day

~ideas
## Ideas

We can afford to be generous because we claim to be the best.
Yes, we're more expensive, but aim to be the best
in our category.
We can afford to throw around
low prices and high margins. 

~method
## Methodology

- [The meditator](##meditator)
- [Computer vision](##cv)
- [The screen](##screen)

~screen
## The screen

* The meditator's 30-inch screen always shows 8 different camera feeds
* 1 of those feeds plays recordings of breeches
* 7 of those feeds present potential false positives, forwarded from the
  CV system.


~cv
## Computer vision

* We use an open-source computer-vision (CV) system to automatically detect breeches
* The CV system has:
    * A near-zero [false negative rate](##cv-fn)
    * A low [false positive rate](##cv-fp)
* Whenever the CV system thinks there might be a breech, the CV system forwards the camera
  feed to the meditator's screen
* The meditator reviews the camera feed and quickly determines whether or not
  the potential breech is an actual breech

~meditator
## Meditator

* A trained meditator watches a screen, taking a 20-minute [break](##break) every 20 minutes
* Whenever a breech occurs on the screen, the meditator pushes the appropriate button
* We frequently play videos of breeches to help keep the meditator focused, and
  to evaluate our own performance

~break
## 20-minute breaks

Frequent breaks help reduce fatigue and increase vigilance.

~chance
## Chance
Take a chance on open business and me.





* We pipe your camera into our computer system


~misc
## Misc

* You can afford the best, and we can accommodate you
* You pay the minimum price, in exchange for a fair deal
* Fair means, we split it 50-50, like a temporary partnership
* Because it's fair, there's 100 points of value that's being exchanged each way.
* 

Imagine you want to do perimeter video surveillance in-house.
It would cost you $X if you were to use our model.

Or, you can pay us 2$X, we'll do it for you, you won't have to assemble an
elite team.

You can even hire us for a while, then drop us and assemble your own elite
team later.

No commitment unless you want to lock down a price

The best way to get away with high profit margins is transparency.

Price formula

- It's [a fair deal](##fair)

No commitment unless you want to lock down a price


* Our cost is primarily determined by:
    * The [cost of meditators](##cost-meditators)
    * The [accuracy](##cv-accuracy) of the computer-vision system


- [Fair](##fair)
- [Investors](##investors)
