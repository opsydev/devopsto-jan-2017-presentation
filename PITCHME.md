#HSLIDE

# DevOps without experience or money
### Raveesh Nagpal
### Shore Consulting Group Inc.


#HSLIDE

# Who is is this presentation for?

- Me a year and a half ago. <!-- .element: class="fragment" -->


#HSLIDE

# But seriously why are we all here?


#VSLIDE

- Can't buy five units of devops. <!-- .element: class="fragment" -->
- Case studies are a great way to figure out how to do devops. <!-- .element: class="fragment" -->
- Lack of information about how smaller companies do devops. <!-- .element: class="fragment" -->


#HSLIDE

## Overview of what we'll be talking about:

- Overview of kind of work we do <!-- .element: class="fragment" -->
- Technological challenges we faced <!-- .element: class="fragment" -->
- Cultural challenges we faced <!-- .element: class="fragment" -->
- Scenarios and lessons that we went through on our devops journey. <!-- .element: class="fragment" -->
- Takeaways. <!-- .element: class="fragment" -->


#HSLIDE

## Setting the stage:

- Consulting firm specializing in public sector. <!-- .element: class="fragment" -->
- Application maintenance and support work. <!-- .element: class="fragment" -->
- Multiple clients, multiple projects and multiple messes. <!-- .element: class="fragment" -->


#VSLIDE

## Technological challenges:

- We don't do operations. <!-- .element: class="fragment" -->
- In most cases throwing over the wall is our only option. <!-- .element: class="fragment" -->
- No in-house expertize regarding ops. <!-- .element: class="fragment" -->
- Microsoft  <!-- .element: class="fragment" -->


#VSLIDE

## Cultural challenges:

- People on multiple projects in multiple teams. <!-- .element: class="fragment" -->
- No easy way to figure out a common thread between projects.  <!-- .element: class="fragment" -->
- No silos to break. <!-- .element: class="fragment" -->


#HSLIDE

#### Scenario 1: 
## Get people to communicate more.
##### I mean, how hard can this be right...


#VSLIDE

## Slack <!-- .element: class="fragment" -->

- Trial run with a small team. <!-- .element: class="fragment" -->
- Set up webhooks and other goodies.  <!-- .element: class="fragment" -->
- Invite all the devs to it.  <!-- .element: class="fragment" -->
- Create channels for projects.  <!-- .element: class="fragment" -->
- chirp.....chirp.....chirp.....chirp....  <!-- .element: class="fragment" -->


#VSLIDE

## Why is no one else using slack?

- People kept forgetting to log in. <!-- .element: class="fragment" -->
- Some devs weren't sure how it even worked. <!-- .element: class="fragment" -->
- But email works for me. <!-- .element: class="fragment" -->


#VSLIDE

## One trick that'll get your company on chatops!

#### Actually it's two things <!-- .element: class="fragment" -->

- Install slack desktop client on their machines as part of an introduction. <!-- .element: class="fragment" -->
- All emails are responded with: "Check Slack". <!-- .element: class="fragment" -->
- All direct messages are replied to in the channels. <!-- .element: class="fragment" -->


#HSLIDE

#### Scenario 2: 
## How to fail at CI/CD
##### How hard can good, fast and cheap be.


#VSLIDE

# Turns out it is surprisingly hard.


#VSLIDE

## Bottlenecks and showstoppers:

- Time
- Cost
- Experience


#VSLIDE

## Cloud was a no-go:

- Everyone needed admin access
- Microsoft 
- Left as is for indefinite periods of time


#VSLIDE?image=assets/lack_rack.jpg


#VSLIDE 

## Why build our own:

- Cheap(er)
- HyperV: Lower learning curve
- Microsoft Partner pack: Licensing is simple(r)