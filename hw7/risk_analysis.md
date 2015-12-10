# Homework 7: Risk Analysis

## Primary Source of Risk

This project's primary sources of uncertainty and risk seems to be related to our need to create components which integrate with our restaurant parters' systems. These will, for example, be required to collect information on current capacities and reservation submissions. Currently we do not even know how many systems are out there, let alone their technical details.

The uncertainty about this is a risk which currently permeates various aspects of the project. A majority of the items below touch on different aspects of this primary risk: items 1, 2, 3, 5, 6, 7, and 8. (These items are marked with asterisks.)


## 1. Personnel shortfalls*

We may not have enough personnel to perform all of the integration work required for our partners's systems. This is a consequence of not knowing (1) how many how many external systems we will we will need to target and (2) their technical requirements.


## 2. Unrealistic schedules and budgets*

Because of our uncertainties related to the amount of work to be involved in integration with our partners' systems, we do not yet have accurate schedules to implement all of the integration work. The consequences of this on our budget are currently unknown.


## 3. Developing the wrong software functions*

We currently expect that integration with Facebook or even other social media platforms will be much more straightforward than integration with partners' systems. It may be the case that we would create better value from our investment by focusing on developing social media integration.


## 4. Developing the wrong user interface

We are developing an iOS application, but it may be possible that we should be focusing on a web interface. While designing the iOS application, it may be wise to try to make design decisions (esp. back-end design decisions) which can support a web interface at some later point.


## 5. Gold plating*

Which partners' systems we should support is currently uncertain. Ideally, we would support everything out there, but this is likely not possible. We should therefore be cautious and intentional about choosing which systems with which we integrate. Because of this, we should be careful about trying to integrate every identified system, as additional systems may add little value.


## 6. Continuing stream of requirements changes*

Early tasks in the project will elicit requirements. However, there is currently a risk of imprecision here. Our initial assumptions about the purpose and the goals may change. In particular, we should be careful about selecting which partners' systems we should support. In fact, we may find that this risk is great enough we may wish to pivot away from supporting any partner integration and instead focus on social media integration.


## 7. Shortfalls in externally performed tasks*

Partners' systems may have greatly differing capabilities. Some may not have enough data for us, and we will need to compensate for this in our system so that user-facing features are adaptive by a the capabilities of the partners' system.

We may also need to be concerned about accurate data collection from partners. It is not unreasonable to expect that in a busy restaurant that the restaurant's system is not always accurate.


## 8. Shortfalls in externally furnished components*

We expect that the features provided by various partners' systems may vary greatly. It may also be that the restaurants with which we wish to partner do not have systems with which we can integrate.

One particular shortcoming to watch for: a partner's system may not be able to notify our system of availability changes fast enough for our user's expectations. This could lead to breaking a user's expectations because they were given inaccurate information (e.g. our system allowed them to make a reservation, but the place was already fully booked).


## 9. Real-time performance shortfalls

Many users may be trying to make reservations simultaneously. We will need to think about how to perform near real-time reservation transactions and availability updates.


## 10. Straining computer science capabilities

We do not expect that the algorithmic challenges posed by this project will strain the bounds of what tractability or computability bounds. Algorithmically, it should be pretty straight-forward. However, we may run into some interesting distributed computation and synchronization challenges. We don't know enough about these complexities to be able to say at this time.
