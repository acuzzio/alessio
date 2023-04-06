---
title: Retropaths
datuccia: 2020-present
thumbnail: images/portfolio/retropaths2.png
service: Reaction discovery, retrosynthesis.
client: Stanford University
shortDescription: This is a software package that simulate chemical reactions using a graph-based template procedure.

---
In this high throughput chemistry software, molecules are treated as graphs, and templates describe a chemical reaction in terms of its core structure, the edge edits and “R” groups, which are wild cards. Importantly, the use of graph theory ensures that the template generates all possible regioisomers.

<img src="/images/portfolio/retropaths.png" alt="retropaths" width="100%"></img>

However, a chemical reaction can be composed of more than one step, and it can be accompanied by side reactions. That is why we introduce the concept of a reaction pot, which consists of reagents and environment molecules along with reaction conditions. In the pot all the templates that can apply are applied until convergence, and a reaction network is formed, where the nodes represent reaction intermediates and products, and the edges are the reactions linking them.

At present, the predicted reaction networks do not consider rates and yields. But this strategy can be combined with *ab initio* calculations to enhance the predictive quality of the networks using transition state theory and kinetic models.

<img src="/images/portfolio/retropaths1.png" alt="retropaths1" width="100%"></img>
