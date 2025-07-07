A repo containing all the releases of Priority Education.
Initial pre-release. Build 0.

We're still waiting for a response from CleverTap's team on the possibility of using the "Session Concluded" system event for live behavior tracking. As of now, it seems like the "Session Concluded" system event doesn't gets pushed until the next time the app launches. This renders the live tracking unusable with this event.

For now, we are deploying a timer-based DEMO journey.
This is an overview of one of the journeys:

<img width="686" alt="image" src="https://github.com/user-attachments/assets/53482302-db4d-4108-9b26-1eb765f26750" />

To engage in this journey, first visit the Harvard University screen and click ‘Like’ it.
If you do not click ‘Apply’ within an hour of ‘Like’-ing it, you’ll receive a promo code to waive the application fee. This promo code is valid until August 26. If you apply by the deadline, you’ll receive a push notification without a promo code for Harvard’s merchandise.
However, if you click ‘Apply’ within an hour of ‘Liking’ it, you’ll receive a push notification containing a promo code for Harvard’s merchandise.

I am aware of the bugs below, and I am trying to fix them as soon as possible:
- Screen goes blank if you click the 'back' button twice.
- Several minor UI bugs
  
I will create more demo journeys over the week and fix the critical bugs.

The source code in its current state is very disorganized. I hope to restructure them into a Model-View-ViewModel (MVVM) pattern in the near future.

Please find the releases in the 'Releases' page on the right.
