# Analog Activity 1: Functions

This is one game during which you'll earn points toward the semester bonus.

Today, your team will fight the Trogg.

## Playing the game

### Warmup round

Duration: ~10 minutes

The instructor will describe various functions and solicit inputs from the class, and it is teams responsibility to determine what each "function" does based on the results.

### The Trogg

Duration ~20 minutes

Each team will have a chance to fight the Trogg. But, first we'll begin with some training: prepare well enough, and the challenge of the Trogg should be easy!

Before we train, though, it might help to know a bit about the Trogg. Though more complex than a simple definition can capture, the Trogg is a creature which prevents students from scoring points on activities. To do this, it uses both strength and smarts to outwit them.

You will be allowed to strategize before the event.

#### Training

Note: Players start with values of `1` for each statistic

1. Your team leader will receive a "training regimen" from the instructor
2. Your group should sequence the training regimen to give your team the best chance to defeat the Trogg
3. To set up your training regimen, the team should sequence the components, organized by the various broader tasks
  * These are grouped into:
    * `strength`
    * `intelligence`
    * `luck`
  * `strength` and `intelligence` are "raw" stats, `luck` always _adds_ itself to these scores
4. From this regimen, you may choose `3` operations to train (i.e. you have `3` instructions)
5. Once complete, tbe instructor will verify the training plan and walk through the results with the team

#### Fighting the Trogg

1. Choose a representative from your team to be its "champion," who will undergo your training program
2. The champion will use the set of training instructions to calculate the final values of `strength`, `intelligence`, and `luck`
  * This involves using an additional function: the `roll` function which:
    * Accepts one parameter -- the maximum number of points that one could add to a given skill
3. Once trained, the Trogg senses a challenge and appears; its own training schedule is unknown to you, but you can bet it has been working out
4. Using the `attack` and `defend` functions, a battle commences, consisting of three rounds of attack and defense
  * `attack` uses whatever values you have remaining in your respective categories to attempt to decrese and opponents score of the same type
  * `defense` decreases a category by a score of the same type
5. If it becomes clear to the Trogg that you're stronger after these `3` rounds, it runs away with a promise to return at a later date
  * Here, "stronger" means that your final `strength` and `intelligence` scores remain higher

##### Catalog of functions

|Function |Parameters  |Description |
|:--------|:-----------|:-----------|
|`roll`   |`1 integer` |Returns a value up to the value of the integer "passed" |
|`train`  |`1 integer`, `1 string` |Adds the integer value to the appropriate player statistic |
|`attack` |`1 integer`, `1 string` |Attempts to reduce the Trogg's statistic of the same variety by the `integer` value |
|`defend` |`1 integer`, `1 string` |Attempts to reduce the player's statistic of the same variety by the `integer` value |

## Scoring

* Defeating the Trogg is worth `10` points toward your team's total semester score

## Additional reminders and guidelines

* You must complete the activity [reflection](writing/reflection.md) to receive full credit.

## Debrief

Duration: ~15 minutes

The course will reconvene as a whole to discuss conclusions drawn or arising from the activity.