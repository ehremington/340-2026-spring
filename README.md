# Spring 2026 Daily Log


## day 10 | 260204 W

We worked through problem 1.2 and talked through a couple of others that I want you to do. Homework is Problems 1.2, 4, 5, 7.

## day 9 |  260202 M

Maxwell's Equation's are rich and worth another shot, so we will work through them again, this time without some of the simplifying assumptions that we made last class. In particular we will talk about the charge density ( \\(\rho\\) ) and the current density ( \\(\vec{J}\\) ), and we will look through the places that those will appear in optics. To be precise: 

$$\rho = \cancel{\rho_{\mathrm{free}}} + \rho_p$$
$$\vec{J} = \vec{J}_{\mathrm{free}} + \cancel{\vec{J}_m} + \vec{J}_p$$

The scratched out terms here are because of what we typically deal with in optics, that is no free charge density and no current density coming from magnetization, either paramagnetic or diamagnetic. What remain are the polarization charge density and the polarization current density as well as any free current density that would be present in a conductor (so think a mirror). 

The result of all of this is a wave equation that has several important differences from last time:

$$\nabla^2{\vec{E}} - \mu_0 \epsilon_0 \frac{\partial^2 \vec{E}}{\partial t^2} = \mu_0 \frac{\partial \vec{J}_{\mathrm{free}}}{\partial t} + \mu_0 \frac{\partial^2 \vec{P}}{\partial t^2} - \frac{1}{\epsilon_0} \nabla \left( \vec{\nabla} \cdot \vec{P} \right)$$

Here there are three terms on the right side that are important in different contexts. The term with free current density will be important with reflection and mirrors. The term in the middle will be important when we have light going through some kind of dielectric material. The last term will be important when we have anisotropic materials like certain crystals.


## day 8 | 260130 F

We will finally look at the mathematical definition of a wave, and also see how that form can solve the partial differential equation of a wave, and then finally see how Maxwell's equations can be manipulated into a wave equation. 

So a wave function is any kind of mathematical function that has a \\(kx - \omega t\\) function within it. We saw this yesterday when I was showing you different kinds of functions that were plotted as a function of x, but that I could drag a slider and show how that function behaved as time went by. 

We then used this form to show that if a function had this form, then we could take some partial derivatives of that function and get a partial differential equation known as the *Wave Equation*. This is the equation that looks like this:

$$\frac{\partial^2 f}{\partial x^2} = \frac{1}{v} \frac{\partial^2 f}{\partial t^2}$$

We then used Maxwell's equations (in particular the Maxwell-Faraday equation) to show that this would produce a wave equation. To do this we took the curl of that equation and worked through the implications:

$$\nabla^2 \vec{E} = \epsilon_0 \mu_0 \frac{\partial^2 \vec{E}}{\partial t^2}$$

This means that the velocity of light could be gotten from two constants that are known from experiments in electricity and magnetism:

$$v = \frac{1}{\sqrt{\epsilon_0 \mu_0}} = 2.998\times 10^8 \, \mathrm{m/s}$$

## day 7 | 260128 W

Today we worked on the definition of a wave. We started Chapter 1, but we are going about it a little bit backwards. I showed some excellent python demos that you can download and run with jupyter lab here.

## day 6 | 260126 M

Snow day!

## day 5 | 260123 F

Today we worked on homework together, specifically problems 0.17 and 0.20.

## day 4 | 260121 W

We talked about complex numbers in more detail and worked through some examples. 

Homework is problems 0.14, 17, 18, 20

## day 3 | 260116 F

We talked today about gradient, divergence and curl. We cover the Laplacian though we will see more of that. We also covered the Divergence Theorem and Stoke's Theorem from a high level and then began to talk about complex numbers. 

## day 2 | 260114 W

We continued to work through some math problems, reviewing homework on cross and dot products as well as get into the gradient, divergence, and curl.

## day 1 | 260112 M

We reviewed the syllabus and talked through some introductory things related to optics. We began working through Chapter 0 in the textbook, reviewing some concepts from 204 and reviewing some math. Homework for next time is P0.1,2,3. 

## day 0

The book is a free pdf that can be found here: [https://optics.byu.edu/docs/opticsBook.pdf](https://optics.byu.edu/docs/opticsBook.pdf)

I recommend you download a copy of it and put it somewhere where you can access it quickly and read it. You can also order a very cheap printed copy by going here:  [https://www.lulu.com/shop/justin-peatross-and-michael-ware/physics-of-light-and-optics-color/paperback/product-1kwyendg.html?page=1&pageSize=4](https://www.lulu.com/shop/justin-peatross-and-michael-ware/physics-of-light-and-optics-color/paperback/product-1kwyendg.html?page=1&pageSize=4)



    [NbConvertApp] Converting notebook README.ipynb to markdown
    [NbConvertApp] Writing 2518 bytes to README.md

