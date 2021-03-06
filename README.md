## Learn Autovalue

Quickstart for working with `AutoValue` (which is an immutable Java value class generator). The class structure of the `AutoValue` class in this quickstart is the same structure found in the `Beam SDK codebase`.

Having a static inner value class (i.e. non top-level) can be seen in `BigQueryIO` [here](https://github.com/apache/beam/blob/master/sdks/java/io/google-cloud-platform/src/main/java/org/apache/beam/sdk/io/gcp/bigquery/BigQueryIO.java#L1706) and in the `PTransform style guide` [here](https://beam.apache.org/contribute/ptransform-style-guide/#language-neutral-considerations).


### What is an immutable class?
- Check out this [article](https://dzone.com/articles/how-to-create-an-immutable-class-in-java) to find out. 
- Hint: if you look at the `generated code`, you will see that the generated-class is set to `final` (making it an `immutable class`).
- Side note: the `PTrasform style guide` requires you to extend the PTransform class into an immutable class (which is automatically achieved via AutoValue). Hurray!

### To run this code, clone this repo, and then open intelliJ

```
git clone https://github.com/amegahed1994/learn_autovalue.git
```
