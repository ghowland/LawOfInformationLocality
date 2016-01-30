# Howland's Law of Information Locality

For a unique set of information, if a decision needs to be made and accuracy is critical, all non-local data is invalid.

## Unique Set of Information

A unique set of information is created any time you abstact any state into a single entity.  This could be an environment in a moment of time (fixed state for that moment), or it could be a physical unit (such as a hard drive) in a given moment.

Uniqueness requires constraint, so if you had a physical unit (such as a disk drive) you could consider either a given moment, or a set of moments (total life-span of this drive) as one unique set of state.  

If you have more than 1 physical thing, then you must consider the set of them as a given unique state.  The important thing for qualifying uniqueness for this Law is that nothing can be anonymous, nothing can be random, we are talking about a particular set of information, that is a local set of information.

#### Unique Set of Information, as a Population

- When the population size is one...
- ...And you care about the accuracy of your data to be as precise as possible...
- ...Only local information is valid...
- ...And no external data can determine anything about this single unit's single instance (now)...
- ...Because all it's state data is unique and local to that single unit's single instance's current state.

To lay out the requirements for this to be true:

- You have a single unit at a single instance in time.
- You need to make a decision about this unit that requires accurate data, because it's important that whatever it is that you are going to do needs to provide a result that meets your goals.

## Accuracy Is Critical

By accuracy being critical, I mean:

- That it is critical that the decisions made from whatever information gathering methods are used...
- ...Provide the highest chances to succeed with the specified goals...
- ...Yielding the best results possible...
- ...Under the realities of the situation.

In short, when you really want whatever it is you are going to do, to work.

## Non-Local Data

Non-local data is anything that is not inside the stated unique set of local information.  If you have a given single rotating disk drive at a given time as the unique set of information, then only information contained by the physical states (including magnetic/etc states, in which data is stored) is included.  Data about that series of rotating disk drive's manufacturing defects is not valid, because while that may be statistically significant for a large-enough populatio of data, it does not describe anything about the exact state of this single rotating disk drive.

You could also include all the set of non-physical data if you wanted to reference the data that was stored in the magnetic/etc states, but this could also be considered it's own unique set of information, separate from the physical state of the device.

What determines the local data set is how you are looking at the problem, as that defines what is local to your information set, and what is non-local (external) to your information set.

## Local-Data-Only Problems

What this law defines are **"Local-Data-Only"** problems.  These are problems where external data is not valid.  Having a label of a "Law" provides an easy method to point to this treatise to get full information about this, but in common communication saying it is a "Local-Data-Only" problem is a much shorter and easier to way to communicate what needs to be communicated.

When I think about these problems for myself, I think about them with the "Local-Data-Only" label, which provides sufficient clarity for me.

# Examples

Because this concept seems to be currently overlapped by other concepts, it has not been easy to explain how it exists independent from other concepts.

I believe this is currently a gap in our collective understanding, although when seen from "common sense" perspective it is obvious.  Once we start to look at problems intellectually, we abandon our "common sense" mechanisms to work with more refined and precise mechanisms, which happen to just not include a mechanism for separating out local-data-only problems from problems where non-local data is valid.

My plan to solve this is through exhaustion.  I will provide an exhaustive number of examples, for many different cases, to underline cases in which only local-data is valid.

These define "Local-Data-Only" problems.

### Example:  Driving and Encountering an Obstacle

[Example: Driving and Encountering an Obstacle](examples/driving.md)


# Background

I wrote this in the theme of technological self-named laws, when one wants to make a point and have a label to reference that point.

Naming it after myself is primarily because it is my assertion that this is true, and I am not finding consensus or a way to even easily discuss this topic because there does not seem to be matching prior art.  So having a unique label to reference this by is required to differentiate it from other ideas that are not covering the same material.

If you can invalidate this Law, let me know and I will update it accordingly.

I wrote this because there is a real problem going on with people ignoring local data, when it is the local data that will inform them on what their current problem-state is, and they are often looking outside their local data to determine what to do, and this causes problems.  It happens all the time, every day, to every person I know, and so I am writing this to point out this issue so it can become known, and thus can be addressed appropriately.

Local-data being required for local-data-only problems does not invalidate the use of non-local data for all sorts of other uses, such as using statistics (non-local data) to make a decision about a unique set of data, when accuracy is not critical.  Or when using statistics against a large-enough population, or where we only collect small amounts of local data, and again, where accuracy is not critical.

Accuracy being critical is a key element to this.  Statistics take into account an amount of error, as acceptable.  When that is not acceptable, than they are invalid.

**You can see the background for when I testing whether there was already prior art for this here:**

https://github.com/ghowland/StatsInvalidWhenPopIsOne
