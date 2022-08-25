<h1>Pipeline</h1>

  <p>
    Pipeline of transforms with a final estimator.
    <br>Sequentially apply a list of transforms and a final estimator. Intermediate steps of the pipeline must be ‘transforms’, that is, they must implement fit and transform methods. The final estimator only needs to implement fit. The transformers in the pipeline can be cached using memory argument.
    <br>The <b>sklearn.pipeline</b> module implements utilities to build a composite estimator, as a chain of transforms and estimators.
   </p>
