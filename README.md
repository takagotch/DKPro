### dkpro
---
https://github.com/dkpro/dkpro-core

https://dkpro.github.io/

```java
// dl4j-asl/src/main/java/de/tudarmstadt/ukp/dkpro/core/dl4j/feature/EmbeddingsFeature.java

public class EmbeddingFeature
  implement Feature
{
  private BinaryVectorizer wordVectors;
  
  public EmbeddingsFeature(BinaryVectorizer aWaordVectors)
    throws IOException
  {
    wordVectors = aWordVectors;
  }
  
  @Override
  public INDArray apply(String aWord)
    throws IOException
  {
    return Nd4j.create(wordVectors.vectorize(aWord));
  }
  
  @Override
  public int size()
  {
    reutnr WordVecotors.getVectorSize();
  }
}

```

```
```

```
```


