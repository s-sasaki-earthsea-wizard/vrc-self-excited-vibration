# Tacoma Narrows Bridge Presentation Script (English)

## Slide 1: Title Slide

Hello everyone, today I'll be talking about "A Pendulum Whose Amplitude Increases with Wind!?"
As shown in this title image, we'll explore the physical mechanism behind this famous bridge collapse that occurred in 1940.

## Slide 2: Self-Introduction

Let me briefly introduce myself. My name is Same (pronounced "sah-meh"). I work as a freelance software engineer while studying at an online university. My areas of expertise include computer vision, specifically image recognition and point cloud processing, spatial information processing, geographic information systems, remote sensing, and cloud infrastructure design. You can find more information about me on GitHub, YouTube, and Speaker Deck.

## Slide 3: Today's Topics

Here's an overview of what we'll discuss today. First, we'll examine why the Tacoma Narrows Bridge collapsed on November 7, 1940. To understand this, we'll explore the equations of harmonic oscillation and damped oscillation, and look at a simple pendulum model. Then we'll discuss Bernoulli's principle, lift, and negative lift. We'll focus on oscillation equations with negative damping from lift forces, and the mechanism of self-excited oscillation. You'll see how a small change in an equation can dramatically alter the outcome!

## Slide 4: Tacoma Narrows Bridge Collapse
The Tacoma Narrows Bridge collapsed on November 7, 1940. Amazingly, the wind caused the bridge to undulate dramatically before its eventual collapse. There's actually footage of this famous disaster, showing incredibly dramatic images. From this photo, you can see just how severely the bridge deformed before falling.

## Slide 5: The Current Tacoma Narrows Bridge
After the collapse, the Tacoma Narrows Bridge was rebuilt in 1950. In 2007, a second bridge was constructed to accommodate increased traffic. Throughout today's presentation, when I refer to the "Tacoma Narrows Bridge," I'll be talking about the original bridge that collapsed. As you can see in this photo, the current bridges have much more stable structures.

## Slide 6: Important Notes
Before we continue, I should note a few things. The actual cause of the bridge collapse was more complex than what we'll discuss today. Modern bridge design uses wind tunnel experiments and numerical simulations. However, today we'll focus on the simplest model to enhance understanding. We'll specifically examine the mechanism of self-excited oscillation.

## Slide 7: Equations of Oscillation
Now let's dive into the main topic, starting with the equations that describe oscillation.

## Slide 8: Pendulum Motion: Harmonic Oscillation
Let's start by considering the motion of a simple pendulum. When you lift a pendulum and release it, gravity creates a restoring force that pulls it toward the center. Due to inertia, the pendulum doesn't stop at the center but swings to the opposite side. The restoring force then pulls it back toward the center again. This repetitive motion creates the pendulum's oscillation, which is the basic mechanism of harmonic oscillation.

## Slide 9: Equation of Harmonic Oscillation
Mathematically, harmonic oscillation is represented by this equation. Here, m is mass, d²x/dt² is acceleration, and kx is the restoring force. The general solution takes this form: x(t) = A cos(√(k/m)t + φ), where A is amplitude and φ is the initial phase. This oscillation is called harmonic oscillation, and in an ideal state, it would continue forever.

## Slide 10: Equation of Damped Oscillation
In reality, pendulums don't oscillate forever. Damping forces like air resistance and friction cause the oscillation to gradually decrease. So we add a damping term to the equation of motion. This term, β(dx/dt), represents the damping force and allows us to model more realistic oscillation behavior.

## Slide 11: General Solution for Damped Oscillation
The general solution for damped oscillation looks like this. The exponential function exp(-βt) creates a decreasing amplitude over time. Looking at this graph, you can see how the oscillation gradually diminishes. This is the actual behavior of pendulums we observe in everyday life.

## Slide 12: Lift and Negative Lift
Now we come to today's main topic: lift and negative lift forces caused by wind.

## Slide 13: Fluid Dynamics
Air and water are examples of what we call "fluids." The forces that wind or water flow exert on objects can be understood through fluid dynamics. This image shows how fluid flows around an object. These flow patterns create forces on the object.

## Slide 14: Bernoulli's Principle
An important law relating fluid velocity and pressure is Bernoulli's principle. According to this principle, when fluid velocity increases, pressure decreases, and when velocity decreases, pressure increases. The equation looks like this: p + (1/2)ρv² + ρgh = constant. Since we're dealing with air today, we'll ignore the potential energy term due to gravity because it's relatively small.

## Slide 15: Lift
Applying Bernoulli's principle helps us understand how lift works. When a plate is tilted with its left side up, the fluid flowing over the top moves faster, creating lower pressure. Conversely, the fluid below moves slower, creating higher pressure. This pressure difference generates an upward force on the plate - lift. This is the same principle that allows airplanes to fly.

## Slide 16: Negative Lift
Conversely, when a plate is tilted with its right side up, the fluid above moves slower, creating higher pressure, while the fluid below moves faster, creating lower pressure. This results in a downward force on the plate - negative lift. The key point is that depending on the fluid flow and the plate's angle, forces can be generated in either upward or downward directions.

## Slide 17: Applications of Lift and Negative Lift
These principles are applied in various fields. Airplane wings use lift to fly. Formula 1 race cars, on the other hand, are designed to generate negative lift to improve stability during cornering. This negative lift pushes the car down onto the track, enabling high-speed driving.

## Slide 18: Self-Excited Oscillation
Now we'll discuss self-excited oscillation, the key to understanding the Tacoma Narrows Bridge collapse.

## Slide 19: Mechanism of Self-Excited Oscillation
When a pendulum is exposed to wind, it experiences lift and negative lift forces as we discussed. The crucial point is that these forces can sometimes work to increase the oscillation. This phenomenon is called self-excited oscillation. As shown in the diagram, upward and downward forces act on the pendulum depending on its position, amplifying the oscillation.

## Slide 20: Analogy for Self-Excited Oscillation
A good analogy for self-excited oscillation is pushing a swing. When you push a swing in time with its oscillation, the amplitude increases, right? The same thing happens with lift forces from wind. When wind applies force at just the right timing, the oscillation gradually increases.

## Slide 21: Equation of Self-Excited Oscillation
Mathematically, self-excited oscillation is represented by an equation where the damping term has a negative sign. In normal damped oscillation, the coefficient β has a positive sign, but in self-excited oscillation, it becomes negative. It's just a change in sign, but let's see what results this produces.

## Slide 22: General Solution for Self-Excited Oscillation
Looking at the general solution for self-excited oscillation, the exponent in the exponential function becomes positive. What does this mean? It means that as time passes, the oscillation amplitude increases exponentially! This graph shows how the oscillation grows over time. It's the complete opposite of normal damped oscillation.

## Slide 23: Why Did the Tacoma Narrows Bridge Collapse?
With our understanding so far, we can now explain why the Tacoma Narrows Bridge collapsed. The mechanism of self-excited oscillation was at work, causing the wind to increase the bridge's amplitude of oscillation. Mathematically, the amplitude grows exponentially, but in reality, there's a limit to what a bridge can withstand. When the oscillation exceeded this limit, the bridge collapsed.

## Slide 24: Summary
Let's summarize today's discussion. We learned that a pendulum's basic motion can be described with harmonic oscillation equations, and adding a damping term allows us to model real pendulum behavior. We then saw how fluid flow and object tilt can create lift or negative lift forces. Finally, we understood how these lift forces can cause negative damping, leading to self-excited oscillation. It's fascinating how a simple change in the sign of the damping term can drastically alter the result.

## Slide 25: One Sign Changes Everything!
This slide compares two equations of motion. The top equation represents normal damped oscillation, while the bottom one represents self-excited oscillation. Just one sign difference produces completely opposite results! The left graph shows oscillation gradually decreasing in damped oscillation, while the right graph shows oscillation increasing exponentially in self-excited oscillation. This is a beautiful example of how mathematics and physical phenomena intertwine.

## Slide 26: Additional Notes
As additional information, I should mention that the actual fluid dynamics of bridges is much more complex. The Tacoma Narrows Bridge collapse is thought to have been caused by aeroelastic flutter, and torsional vibration was also a significant factor. Self-excited oscillation wasn't the only cause. However, today we focused on the simplest model of self-excited oscillation for better understanding.

## Slide 27: Call for Lightning Talk Presenters
The Physics Community is looking for Lightning Talk presenters! Any genre is welcome. Please contact the Physics Community Discord server if you're interested. If we don't get any volunteers, the organizer will have to do another "Giant Recital" disguised as a Lightning Talk session... (laughs). We'd love to hear your presentations!

## Slide 28: Announcements
Finally, our next meeting is scheduled for May 17th. We're planning to watch physics videos on YouTube together. If you have a video you'd like to watch as a group, please let us know! Your suggestions are most welcome.

Thank you for your attention! If you have any questions, please feel free to ask.