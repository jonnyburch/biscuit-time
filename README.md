# biscuit time

## Problem

I keep eating way too many biscuits. Like, we'll do a big shop and then I'll eat a week load of biscuits in a night, mindlessly.

I'd like to be able to buy biscuits in bulk, then be able to ration myself (and my wy wife who is a fellow sufferer)

## Idea

A biscuit barrel that only opens based on a set of conditions. This would mean that we could load up the biscuits when we buy them, then 'qualify' for a biscuit at, say, 8pm every night. But only one biscuit. Maybe two. Maybe both of us have to agree to the biscuit, or a trusted friend.

## Rough implementation

- A physical box that allows us to drop in daily rations of biscuits/sweet treats with a door with a wifi-enabled lock. Likely a password lock (like boris bikes).
- An app with a rules engine that decides whether the box can be opened at any given time. Notifies us when it's biscuit time.

### The box

- Has seven compartments with seven doors? Or just more of a vending machine type vibe that only spits out one at a time?
- How would it speak to the rules engine? Raspberry pi with wifi?
- Does it have a numpad or controller on it? Or does it just 'open'?
- Potentially it's just not connected at all, but creates the same password internally as the app does every day? Or maybe it just becomes open?

### Rules engine

- What are the rules?
    - time windows
    - not been opened yet that day/time window
    - permission given by both parties? (harder)
    
    
### Reporting

- What data is interesting?
    - How many days this week did I get a biscuit?
    - What times of day did I eat my biscuit?
    - What biscuits did I eat (requires some kind of input when box is loaded)
    

## Links

- https://tutorials-raspberrypi.com/connecz-raspberry-pi-kecpad-code-lock/
