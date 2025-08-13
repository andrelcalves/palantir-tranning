# JSON Formats
## To be able to transformat JSON data sources use this as reference:
- https://learn.palantir.com/deep-dive-building-your-first-pipeline/1874719

## Joining, and Aggregations
-Joining and aggregation: Learn how to combine and summarize datasets, while being mindful of potential pitfalls such as duplicates, incorrect join conditions, and the computational expense of joins.
-Materializing outputs: Understand the significance of outputs and why they matter.
-Validating the output of the join: Learn the importance of validating your joined dataset, as joins can sometimes introduce duplicates or errors if not executed correctly.

It is a recommended practice to analyze the outputs of your joins and the techniques introduced in the sections before, such as the Preview functionality, are a great starting point for small datasets. In this section, however, you will leverage a different Foundry tool, Contour, to help analyze the joins that you created in the previous steps. In most cases, you’d be able to do your basic analyses in Preview, however Contour allows you to look through the entire data and discover bugs that would otherwise be impossible to find in Preview.
