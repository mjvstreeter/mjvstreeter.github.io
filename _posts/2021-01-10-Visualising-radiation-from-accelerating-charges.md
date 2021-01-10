---
layout: post
title: "Visualising radiation from accelerating charges"
date: 2021-01-10
---

When a charged particle, say an electron, wiggles around it emits radiation, specifically electro-magnetic radiation which includes things like radio-waves and visible light.
This can be visualised by considering what happens when an object undegoes some form of acceleration.
The information about this acceleration propagates outwards, but only at a limited speed as described by special relativity.
One type of information is the attractive or repulsive force experienced by a charged particle due to the presence of another charged particle.
So if an observer was able to measure the force experienced by a slightly postively charged particle she was carrying in a special container, due to an electron some distance away, she could tell the direction of that electron by the direction of the force.
But because the information is delayed, she would actaully measure where the electron was some small time earlier.
Thats no problem if the electron of interest is just sitting there, but if it starts moving around then it is going to get interesting.

A classic example is a dipole, where the electron performs a periodic oscillation.
In the visualisation below, the information about the electron's position is represented by expanding blue circles, originating from the electron at certain intervals.
The red lines connect points moving away from the charge at the speed of light and at a fixed angle.
These lines can be thought of as the electric field lines resulting from the charge of the electron. 


<video width="480" height="480" controls>
  <source type="video/mp4" src="{{ site.baseurl }}/illustrations/dipole_ramp.mp4">
</video>

As the electron starts to move, wiggles form in the field lines, which then propagate outwards at the speed of light.
The transverse periodic wiggles in the field line, which are seen along mainly to the left and right of the dipole, also carries energy away from the dipole in the form of electro-magnetic radiation.
Our observer positioned somewhere to the right of the dipole could measure the electric and magnetic fields oscillating as a function of time, which could also be detected with a camera or her own eye.
So this dipole is a source of light, and in this visualisation is seen through a purely geometric approach and by knowing that a charged particle generates a radial electric field.

In the case of a static charge or one in constant uniform motion, there are no such field oscillations and therefore no energy is radiating away from the charge.
When the electron moves at a constant speed which is a significant fraction of the speed of light (relative to our stationary observer), the field lines are redistributed as shown below. 

<video width="480" height="480" controls>
  <source type="video/mp4" src="{{ site.baseurl }}/illustrations/constant_motion.mp4">
</video>

In this case our observer sees electric and magnetic fields which change with time, but the only energy flow is in the direction the electron is moving, not outwards away from the charge and so no light is emitted.
This must be the case, as Einstein's Special Relativity tells us that the laws of physics is the same in all inertial frames, and so if no light is emitted by a stationary charge, then this must also be true for a charge in constant motion.

However, we do see that the information about the position of the charge is compressed ahead of its motion.
This is the relativistic doppler effect and is used by particle accelerators to generated short wavelength radiation by combining the previous two examples of dipole radiation and constant relative motion.
This is known as a "Wiggler" and is shown in the visualisation below.
The electro-magnetic radiation emitted by the dipole is compressed in the forward direction.

<video width="480" height="480" controls>
  <source type="video/mp4" src="{{ site.baseurl }}/illustrations/wiggler.mp4">
</video>

Compared to the trajectory electron (shown by the grey line), we can see that the radiation is of a shorter wavelength and the factor by which the wavelength is reduced is related to the forward velocity as a fraction of the speed of light.
Wigglers (called Undulators when the dipole motion is below some threshold) are the basic princples of large scale synchrotron facilities, where they are used to generate intense x-rays.
To do this the electrons a first accelerated to 99.99999% of the speed of light before being wiggled in a set of alternating magnets.
The x-rays produced by this process are used to examine materials, chemicals and biological samples with sub-nanometer precision and are one of the most important scientific tools of the last 50 years and are  flagship scientific facilties in many countries around the world https://en.wikipedia.org/wiki/List_of_synchrotron_radiation_facilities.

