---
date: 2023-10-22T13:00:00Z
draft: false
author: "Luke Beukelman"

title: "Honey Wheat Bread"
recipe:
    - Autolyse Mix:
        Ingredients:
            - Hard white spring wheat flour, whole grain:
                Amount: 720g
            - Water:
                Amount: 520g
        Instructions:
            - Mix until combined.
            - Let sit for one hour.
        Time:
            - Active: 5m
            - Inactive: 1h
    - Yeast Sponge:
        Ingredients:
            - Warm water:
                Amount: 80g
            - Active dry yeast:
                Amount: 2T
        Instructions:
            - Mix until disolved.
            - Wait 10 minutes until sponges.
        Time:
            - Active: 1m
            - Inactive: 10m
    - Honey Wheat Bread:
        Primary: Yes
        Dependencies:
            - Autolyse Mix
            - Yeast Sponge
        Ingredients:
            - Autolyse Mix:
                CREF: Autolyse Mix
                Amount: All
            - Yeast Sponge:
                CREF: Yeast Sponge
                Amount: All
            - Salt:
                Amount: 1T
            - Honey:
                Amount: 1/2C
            - EV Olive Oil:
                Amount: 1/2C
            - Hard white spring wheat flour, whole grain:
                Amount: 100g
                Note: For dusting the surface, anticipate most of this being absorbed into the dough.
        Instructions:
            - >
                Combine all ingredients (except the dusting flour) by forming your
                hand into a flat hook shape and mixing. Mix until dough is firm enough
                to knead on counter.
            - >
                Cover an area on your work surface well with some of the dusting flour.
                Don't use it all immediately, more will be put down as the dough ball
                picks up and incorperated the flour.
            - >
                Knead the dough ball using a stretch and fold method for roughly 10
                minutes. The ending dough ball should be able to be stretched very thin,
                although not quite forming a window pane as per the nature of whole wheat
                flour. Cover the ball in flour as it starts sticking to your hands.
            - >
                Oil the outside of the dough ball and place in a covered bowl to rise
                for an hour, or until dough has roughly doubled in volume.
            - >
                Punch the dough ball down, and split into 2-3 equal portions, form
                into loafs by pulling the dough ball and tucking under. Place in well
                oiled loaf pans, and let rise for another 30 minutes.
            - >
                In the meantime, start preheating the oven to 350 degrees F.
            - >
                Place the pans in the oven, bake for 25-30 minutes, or until the tops
                are lightly golden and sound hollow when tapped.
        Time:
            - Active: 20m
            - Inactive: 2h
---