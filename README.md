# VCBouncer

VC Bouncer was a suggestion from the community (*tbc who contributed the name) as a security guard for the voice chat to link to chat voice.

## Definition

"A bouncer" is 

> bouncer | ˈbaʊnsə |
> 
> noun
> 
> 1 a person employed by a nightclub or similar establishment to prevent troublemakers and other unwanted people entering or to eject them from the premises.

The name is kind of a callback to IRC's days of requiring a bouncer to "stay" in an IRC channel, but also this VC Bouncer would be there to help moderate the VCs!

## Functionality and Purpose
This project intends to be something at first for a Discord Community to:

1. Support mostly VC Channels that are generic e.g. `voice-text-1`, `voice-text-2`.
1. Configure that `voice-text-x` would only be available to users connected to `VC #x`.
1. The project would need to have a 120 second buffer between being inside the VC because:
    1. Some may have Audio issues they can solve in these 2 minutes
    1. Some may want to take the links or part of the context from the VC
   
### Background
When users are chatting in general voice text channels, the agenda or topic for that VC may change.

This means anybody who is reading the `voice-text-1` Text Channel will have no context to most things sent there.

## Goals

### What does this fix?

1. VC Topics can start to vary as noise from other Voice Channel text channels won't confuse users.
1. Discord users will only see the relevant voice text for the channel they are participating in.
   1. This prevents the "I've put the (screenshot, meme, solution) in voice-text" problem in a VC, as there will only be one available channel relevant to that VC.
1. In the future, we could have disposable topics that end up in GitHub Gists that people can refer back to.
    
## Have an idea for VCBouncer?

Please [contribute to the GitHub Issue Queue](https://github.com/stemount/VCbouncer/issues/new) with ideas you have.

Feedback and discussions are also [totally welcome in the GitHub Discussions group too!](https://github.com/stemount/VCbouncer/discussions/1)

### How can I help?!

The Issue Queue is a great place to put to share your views, insights etc.

https://github.com/stemount/VCbouncer/issues/2

https://github.com/stemount/VCbouncer/issues/3

https://github.com/stemount/VCbouncer/issues/4

https://github.com/stemount/VCbouncer/issues/5

https://github.com/stemount/VCbouncer/issues/6

https://github.com/stemount/VCbouncer/issues/7
