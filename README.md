# ARIN121 Assignment 3: Travel Planner

This project extends my Assignment 2 travel planner with an activity menu and a multi-turn option for revising an itinerary.

## What the planner does

The planner supports two activities:

1. **Plan a trip** — creates a day-by-day itinerary with morning, afternoon, and evening suggestions after confirming the destination and trip length.
2. **Revise a trip plan** — updates an existing itinerary from the current conversation or one the traveller provides.

The planner also keeps the Assignment 2 features: it groups nearby activities, gives estimated travel modes and times, adjusts the schedule for a relaxed pace with an afternoon buffer, suggests indoor rainy-day alternatives for outdoor activities, checks ambiguous destinations, and stays focused on travel planning.

## How to use it

If a general travel request does not make the intended activity clear, the planner displays this menu:

> What would you like help with?  
> 1. Plan a trip  
> 2. Revise a trip plan

Choose by number, activity name, or a clear request in your own words. You can switch activities at any point. The planner carries forward useful details—such as destination, dates, duration, budget, interests, pace, and accessibility needs—so you do not have to repeat them.

For a revision, say what you want changed. The planner suggests an adjustment, asks whether it works, and uses your feedback to refine it. When you approve the revision or say you are done, it confirms that the revision is complete.

## Files

- system-prompt.md on the conversational-features branch contains the revised prompt with the menu and trip-revision activity.
- The initial commit on main preserves the original Assignment 2 prompt; the revised prompt is developed on the conversational-features branch.
