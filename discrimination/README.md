# discrimination

## Setup tips

- download conda directly instead of using pip
- install requirements_* that you're going to use
- might need to set python path to grover location export PYTHONPATH=$PYTHONPATH:~/dev/grover/

## Running discriminator

- download models in models/ via download_model.py
- run python3 discrimination/run_discrimination.py -input_data discrimination/input/input.jsonl -output_dir discrimination/output -do_train true
