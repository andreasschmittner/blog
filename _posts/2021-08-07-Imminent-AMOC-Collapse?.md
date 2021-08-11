---
layout: post
title: Imminent AMOC Collapse?
---
The recent paper by [Nicklas Boers (2021)](https://www.nature.com/articles/s41558-021-01097-4) suggests the Atlantic Meridional Overturning Circulation (AMOC) may be about to collapse. It has been picked up by the media with prominent features in the [New York Times](https://www.nytimes.com/2021/08/05/us/gulf-stream-collapse.html), [Washington Post](https://www.washingtonpost.com/climate-environment/2021/08/05/change-ocean-collapse-atlantic-meridional/) and [Guardian](https://www.theguardian.com/environment/2021/aug/05/climate-crisis-scientists-spot-warning-signs-of-gulf-stream-collapse), with misleading headlines and (IMO) too much hype of impending doom. Here I provide a few thoughts based on my own reading of the paper that may help to put it into perspective.

Let me start by noting that the paper is well written and describes a new and interesting approach to analysing AMOC stability. The method is based on simple systems: a non-linear differential equation of a single variable. If such a system has an equilibrium it can be linearized around that equilibrium such that the perturbation (the deviation from the equilibrium) x is characterized by the simple differential equation
$$ \frac{\partial x}{\partial t} = \lambda x + \text{noise}$$, where $$\frac{\partial x}{\partial t}$$ is the rate-of-change of x with time. The equilibrium is stable if $$\lambda$$ is negative since any perturbation will be dampened by the $$\lambda x$$ term, which restores x back towards zero. If $$\lambda > 0$$ the system is unstable since every small perturbation will grow over time.

