# Classification API in Rust

The service reads dados.csv, fits logistic regression with Linfa, serializes the model and serves predictions with Rocket. Start it from the repository root and POST a JSON object containing a features array to /predict.

## Run locally

```sh
cargo run --release
```
