# Constraint-Sets

Learning how to use ConstraintSets to animate whole layout transitions
We create separate layout files and get the corresponding constraints with the ConstraintSet’s clone method, where we can pass a layout resource or an instance of ConstraintLayout
we can  also add and remove constraints dynamically with methods like connect, setMargin etc.
We also apply these constraints by calling applyTo on the ConstraintSet, where we pass our active layout.
With TransitionManager.beginDelayedTransition we can animate this transition the same as we did for placeholders, and optionally we can pass an alternative transition and interpolator, like the ChangeBounds transition and the OvershootInterpolator


