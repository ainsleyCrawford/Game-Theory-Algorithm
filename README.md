# Game_Theory_Algorithm
## Game Theory
Game theory uses mathematical models to predict and understand interactions between rational individuals. It is often used as a way of understanding the world around us, notably in the social sciences, economics and geopolitics. Proponents of game theory advocate its use in designing social, economic and diplomatic policies that induce actors to behave desirably.
## The Prisoner's Dilemma
The prisoner's dilemma—perhaps the most famous example of game theory—is a symmetric, non-zero-sum game which explores whether it is in someone's interest to cooperate or betray. In one version of the prisoner's dilemma two partners-in-crime must decide to cooperate or defect without knowing the choice their codefendant will make. Cooperation from both results in a year sentence each. Double defection results in 2 years each. However, if only one cooperates he walks free whilst his partner serves 3 years. Each suspect knows that defecting means less time in prison whether their partner cooperates or defects: from 3 to 1 should they cooperate; 2 to 0 should they betray. For this reason, each suspect is likely to defect, resulting in 2 years, rather than cooperate, resulting in 1.

In a more general version of this game, users have multiple rounds. They can, therefore, sanction or reward the other player for their past actions. It has been proven that the best strategy is 'tit-for-tat', i.e. responding in kind. The prisoner's dilemma, thus, is of interest to evolutionary biologists who theorise that Homo sapiens is inherently altruistic because this behaviour in an individual increases his/her chance of survival.

The aim of this project is to create an algorithm that implements the 'tit-for-tat' strategy against a future user. A console app will be used for now; the interaction logic could be easily incorporated into WPF at a later date.

## Application Design:
For the algorithm to respond in kind to the user's most recent action—cooperation/betrayl—that action must be passed into an if-statement. A boolean seems most adapted for this role.
