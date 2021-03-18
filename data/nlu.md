version: "2.0"

nlu:
## intent: greet
  examples: |
    - hey
    - hello
    - hi
    - hello there
    - good morning
    - good evening
    - moin
    - hey there
    - let's go
    - hey dude
    - goodmorning
    - goodevening
    - good afternoon

## intent: goodbye
  examples: |
    - good afternoon
    - cu
    - good by
    - cee you later
    - good night
    - bye
    - goodbye
    - have a nice day
    - see you around
    - bye bye
    - see you later

#3 intent: affirm
  examples: |
    - yes
    - y
    - indeed
    - of course
    - that sounds good
    - correct

## intent: deny
  examples: |
    - no
    - n
    - never
    - I don't think so
    - don't like that
    - no way
    - not really

## intent: mood_great
  examples: |
    - perfect
    - great
    - amazing
    - feeling like a king
    - wonderful
    - I am feeling very good
    - I am great
    - I am amazing
    - I am going to save the world
    - super stoked
    - extremely good
    - so so perfect
    - so good
    - so perfect

#3 intent: mood_unhappy
  examples: |
    - my day was horrible
    - I am sad
    - I don't feel very well
    - I am disappointed
    - super sad
    - I'm so sad
    - sad
    - very sad
    - unhappy
    - not good
    - not very good
    - extremly sad
    - so saad
    - so sad
    - bad mood

## intent: bot_challenge
  examples: |
    - are you a bot?
    - are you a human?
    - am I talking to a bot?
    - am I talking to a human?

## intent:book_room
- I want a [room](facility_type)
- I want [rooms](facility_type)
- I want to book [rooms](facility_type)
- I need [2](number)  [deluxe](room_type) [rooms](facility_type) to stay
- I need a [room](facility_type)
- I want a [room](facility_type) in your hotel
- I want [3](number) [rooms](facility_type) in your hotel
- I want to book a [room](facility_type)

## intent:number_of_rooms
- I want [3](number) [rooms](facility_type)
- [2](number)
- [3](number)
- I need [3](number) [rooms](facility_type)

## intent:request_room_cleaning
- I want my room to be [cleaned](service)
- [Clean](service) my room
- I want a [clean](service) room
- [clean](service) my room
- Need a [clean](service) room

## intent:cleaning_time
- Could you send someone right [now](time)
- Right [now](time)
- After [2 hours](time)
- [now](time)
- Could you send someone after [2 hours](time) ?
- [now](time)

## intent:faq/checkin
- What are your check-in timings
- your check-in timings
- check-in timings
- when can i check in?

## intent:faq/checkout
- What are your check-out timings
- your check-out timings
- check-out timings

## intent:faq/cancel
- How do I cancel a reservation?
- Cancel my reservation
- cancel a reservation
- I want to cancel my reservation

## intent:faq/cancel_policy
- What is your cancellation policy?
- your cancellation policy
- I want to know your cancellation policy

## intent:faq/check_restaurant
- Does the hotel have a restaurant?
- Do you have a restaurant?
- restaurant?

## intent:faq/have_breakfast
- Does the hotel offer breakfast?
- Do you serve breakfast?
- Breakfast?
- Can i get some breakfast?

## intent:faq/breakfast_timings
- What are the breakfast timings?
- Your breakfast timing
- Breakfast time?

## intent:faq/restaurant_timings
- What are the timings of your restaurant?
- Restaurant timing?
- Restaurant time?
- When is the restaurant open?
- Restaurant opening time?

## intent:simple
- [Simple](room_type)
- [Simple](room_type) one

## intent:deluxe
- [Deluxe](room_type)
- [Deluxe](room_type) one

## intent:confirm
- Yeah
- Yes
- yes
- That's right
- Yeah. That's right
- Alright

## intent:out_of_scope
- I want an ice-cream
- neither
- I am hungry
- I want french cuisine
- I don't care!!!
- stop

