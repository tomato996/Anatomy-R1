# Anatomy-R1

## Requirements

- **ms-swift** framework, version **3.3.0.dev0** must be installed before running this project.  
  Please refer to the [ms-swift documentation](https://github.com/modelscope/swift) for installation instructions.
  

## Testing Different Methods

To test different methods, you can find a variety of test scripts in the `examples/train/grpo/` directory:

```bash
ls ms-swift-main/examples/train/grpo/
```

Each script corresponds to a different experimental method.  
**Note:** If you want to test the **GPG method**, you must replace the default `trainer` file with the grpo_trainer.py for GPG. Please ensure you use the correct trainer file before running GPG-related experiments.
