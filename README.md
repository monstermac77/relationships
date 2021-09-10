Note: This is currently very free-form because often these are disjoint thoughts that sprang into my mind while I was walking or discussing this topic with friends or strangers and hearing their stories. 

The decision of whether or not to break-up with someone at any given time can probably be expressed as a polynomial (i.e. `ax^i + by^j + cz^k + ...`) where the coefficients (`a`, `b`, ...) are the weights of how important the factors (`x`, `y`, ...) are to the individual (for simplicity, we'll use "you"). If the sum of all of the terms in this polynomial is smaller than some constant `ψ` (where `0 < ψ < 1`), then you feel as though it makes sense to break up with your partner. If the sum is greater than `ψ`, then you feel as though you should stay with your partner. The factors are your perception<sup>1</sup> of their various traits. For example, `x` could be your partner's attitude toward saving money, `y` could be the physical attraction you have to your partner, `z` could be your partner's capacity for empathy or patince, etc. If a factor is unimportant to you, it'll have a small coefficient (i.e. it plays a small role in determining the outcome).

Although it's likely that all decisions thinking beings make could be represented this way (notice what's being explored here is essentially identical to general [classification problems in machine learning](https://www.toptal.com/machine-learning/machine-learning-theory-an-introductory-primer)), we'll stick with using relationships as a means of exploring the polynomial's ability to represent the way we think.

In addition to the primary terms of the polynomial, we also have "bias" terms which are added in and treated the exact same in our decision making as the fundamental (or sometimes even objective) factors. These could pull the decision toward breaking up (racist views, a stigma against their educational background, etc.) or away from breaking up (avoiding the pain of separating finances, avoiding figuring out who is going to move out and who will continue paying for the lease, etc.) 

A wonderful benefit of discussing one's relationship with friends, a therapist, or even a stranger is that when they evaluate this polynomial, they are often not subject to (or subject to different but probably less strongly weighted) bias terms. The better they are at being objective/the more training they have in this (e.g. a psychologist), the smaller and smaller weighted their bias terms are. Moreover, the more removed they are from your life (e.g. a stranger) the fewer bias terms they're likely to have since your action will have no effect on them. This permits them with a profound ability to provide very solid advice, but here's the issue: they can't possibly know or experience all of what you've experienced in the relationship. There lies the catch: your friends / therapist aren't subject to your bias terms, but they don't have the complete information; you have the complete information, but you're subject to your bias terms. 

One approach to this issue is documentation: to the best of your ability, document objectively the variety of terms (factors) that you believe come into play for you and how important they are to you (weights), then provide this documentation to as many of your friends as possible and ask them to evaluate whether they think your partner is someone you should stay with. This documentation could come in the form of a written summary of the relationship (long-form), a pro/cons list (short-form), or perhaps something even more quantititative. A reduced but equivalent version of this problem that can be used to good effect is creating only a cons list and check if the sum of the terms is greater than `(1 - ψ)`. Discussing this documentation with as many trusted people as possible is also advised, as it appears merely the process of discussion is essentially an act of "learning" (i.e. an adjustment process on the weights of the factors). This weight adjustment process also appears in machine learning and is referred to as [training a Perceptron](https://www.toptal.com/machine-learning/an-introduction-to-deep-learning-from-perceptrons-to-deep-networks) in supervised learning.

One might wonder then: why doesn't one just always follow the raw advice of their friends? That is another issue: it seems as though it's difficult to make any decision if it feels like that decision isn't coming from within (likely as a way of protection against undue influence by others). Perhaps this is why the Socratic method or even "reverse psychology"<sup>2</sup> is such an effective form of learning: it lightly tricks the mind into thinking that it is the origination of the idea or belief, and so that idea or belief can be trusted and acted upon. This is also likely why we often kick ourselves for not listening to others in hindsight once we've discovered that they were right: we simply couldn't make the same conclusion as them because of our bias terms. In hindsight, the bias terms have gone to zero, which means we have perfect clarity since we have none of the bias and all of the information, so the solution seems obvious (hence the expression "hindsight is 20/20"). Finally, after breaking up, it seems as though one starts to highly (sometimes over) value the attributes that they felt were missing from their former partner (that is, they have "learned" and positively adjusted the weights of the these factors in the polynomial)<sup>3</sup>.

As mentioned above, sometimes this learning (for an open-minded person) can come from discussion with friends, therapy, or strangers. However, there is no substitute for self-discovery when it comes to learning. Over time, random environmental events will trend the factors in the polynomial (which, remember, are the _percieved_ values) toward their _true_ values, just like the law of large numbers says that the percent of heads when flipping a coin will tend toward 50% as the number of flips goes to infinity (in essense: as time evolves, truth emerges). An example of a random environmental event: your partner getting a dream job in another state and having to decide what to choose between you and their career. An event like this is simply an acceleration of what would have been discovered eventually anyway provided enough time and other random (perhaps less consequential) environmental events, such as deciding how much to spend on a new television (which would help uncover the true difference in attitude toward saving money). These acceleration events are undoubtably painful, often for both parties, because it requires a change in perception and can even induce anxiety, as a concern might grow that the true values of these terms are simply so great that a break-up will inevitably ensue (which of course is anxiety-inducing because of the sunk cost of the relationship, the fear of a now unknown future, etc.). When an argument between you and your partner appears unresolvable (an impasse is reached) and rational argument and explanation appears unable to bridge the gap, it's likely that the _true_ value of a term has been uncovered. If this term is highly weighted for a party, then this impasse can be extrodinarily painful and may result in a break-up. If the term is highly weighted for only one partner, the other partner will experience the ultimate acceleration event: being broken up with non-amicably, which forces a rapid change in perception and anticipated-future that is intensely painful (just like the unanticipated death of a family member). If the term is highly weighted for both partners, it's likely the break-up will be closer to mutual. 

A couple of additional thougts: 
* The constant, `ψ`, which effectively is a threshhold, that the polynomial is compared against is also likely a value that flucuates over time (that is, it's a trainable value). For instance, it's likely that as one ages, `ψ` is adjusted up or down after each relationship. For instance, if it was determined that a relationship went on for longer than it should have, it's likely that this threshold is reduced as an attempt to prevent the next relationship from going on too long. Conversely, if it was determined in retrospect that a break-up was premature, this threshold is likely increased. It's likely the initial condition of `ψ` (when one is young) is set too high, as onlookers often comment that relationships between youngings should have fizzled out long before they do. As one feels pressure to find a partner, either culturally, by family, or by nearing middle life, it's likely that this value is gradually adjusted upward to allow for faster discovery of a compatible partner. 
* It's also likely that friendships can be represented this way, although the number of terms in a friendship is likely much smaller. As explained above, the inverted-parabolic trend of `ψ` over age appers to also apply to friendships.
* With this mental model of relationships, it's no surprise that there is a honeymoon period at the start of a relationship: very little time has elapsed in the relationship and so a large differential between the _percieved_ and _true_ values of the terms can exist. The length of the honeymoon period, then, is likely inversely proportional to the sum of the _true_ differences between all of the factors. As described above, as time goes on, these percieved values tend toward their actual true values (via random discovery, often accelerated by hardship and other environmental factors). The larger the _true_ differences, the faster the honeymoon period will end and the faster the relationship will trend toward break-up. It's reasonable then to conclude that no relationship can survive infinite time or substantial environmental hardship. Every relationship likely would end, it's simply a matter of whether one's life ends first. Random environmental factors simply accelerate this timeline. 
* It can be constructive to think about the "bias" terms as artificial glue that may keep two people together longer than they would have stayed together otherwise. It's thus beneficial to delay or eliminate the introduction of this glue for as long as feasible (e.g. moving in together, getting married, etc.). Marriage is a primary example of this artificial glue: should love not be actively choosing to stay together each day despite the ease of leaving? In many ways, marriage appears to be nothing more than a large-scale social stabilzation tool to keep as many families together as possible. 
* Bias terms can make the calculation of this polynomial very messy. For instance, say a bias term is the idea that "we are destined to be together", and this term gains more and more weight over time as hardships are endured, long distance is survived, etc. Now, when the brain is called upon to evaluate a fundamental term (say, how nice your partner is to you), you're relying on an organ you know is predesposed to conclude what it has been led to believe through years of evidence: "we are right for each other". Depending on the weight of that bias term, this statement could become almost axiomatic, and easily shape how memories are framed. For instance, if this belief is strong enough, the evidence served up might say "I have more fun with my partner in groups" rather than the negative framing which could be "My partner treats me differently when we're alone". In effect, this demonstrates how the evaluation of some terms is going to be subject to selective attention and confirmation bias.

[TODO] the two isosceles triangles and their area overlap, top vertex is starting point. 

Footnotes:

1. It's imperative to note that this is your _perception_ of their trait, not the _true value_ of the trait. The less you know about the person, the larger the difference between these two values might be.
2. Thank you to Amelia Grace Ward for a discussion that led to this insight.
3. Thank you to Monty Evans and Hannah Nayowith for discussions that led to this insight. 
4. Thank you to Nora Kaybe for a discussion that led to this insight.

