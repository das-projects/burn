# Text Generation

The example can be run like so:

```bash
git clone https://github.com/burn-rs/burn.git
cd burn

# Use the --release flag to really speed up training.
export TORCH_CUDA_VERSION=cu113
cargo run --example text-generation --release
```