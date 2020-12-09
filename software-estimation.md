# Software Estimation

## Approaches

### Work Breakdown Structure \(WBS\)

Work Breakdown Structure - bottom-up estimation approach. Also, known as "decomposition and recomposition".

#### Concept

* Break down large tasks into smaller tasks
* Repeat until tasks are relatively easy to estimate \(1-3 days of work\)
* Estimate each task using the 3-point estimation technique
* Compute a total project estimate by summing up the estimates

#### Three-point estimation technique

Come up with 3 estimates for a task:

* Best-case estimate
* Most likely estimate
* Worst-case estimate

Calculate an estimate as a weighted average:

$$
estimate = (BestCase + 4 * MostLikely + WorstCase)/6
$$

#### **Best practices**

* Document the **assumptions** and **decisions** that influenced the estimate
* Group tasks by **feature/epic** and **dependencies** to ease the descoping process
* Split tasks into separate technical areas \(e.g. back-end, front-end, mobile, database, DevOps\)

## Estimation by proxy

#### Concept

* Elicit and count quantifiable components. Good things to count: number of screens, input fields, database tables, endpoints, reports
* Project the estimate based on past experience of the efforts it took to build each component
* Calibrate for project size and quality requirements
  * Example: if the next project contains 20% more database tables, 10% more endpoints, and 30% more UI screens it is likely to take ~20% more effort to build 

#### Best practices

* **Count** when possible. Good things to count: number of screens, input fields, database tables, endpoints, reports
* Don't estimate against differently sized projects. Bigger projects tend to require more effort to develop a single component due to team coordination, integration, and testing challenges
* Don't estimate against projects of different types \(e.g. e-commerce vs blog engine\)

## Best practices

* Split development in **phases**. Helps with building a schedule and parallelizing work.
* Never present a single number, use **ranges**.
* When launching a new project account for a team ramp-up and environment set-up
* Account for scrum overhead, QC, and unit testing
* Use past estimates for your team/organizations to calibrate estimation variables

## References

1. "Software Estimation: Demystifying the Black Art" by Steve McConnell

