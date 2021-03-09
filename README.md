
<p align='center'>
  <a href='https://github.com/alec-tschantz/pymdp'>
    <img src='.github/logo.png' />
  </a> 
</p>

An Python-based implementation of `active inference` for Markov Decision Processes,
based on functions from the `SPM` [implementation](https://www.fil.ion.ucl.ac.uk/spm/doc/)


![status](https://img.shields.io/badge/status-development-orange)

## Installation and Usage

In order to use this code, download the `pymdp` folder into your project
folder and run:

You can install the relevant package versions with using
```bash
pip install -r requirements.txt
```
You can now use all classes and functions via `import pymdp`

## Getting started

See the `pymdp/examples/` folder. For instance, run
```python
python -m examples.agent_demo
```

## Contributing 

If you would like to contribute to this repo, you may have more success with venv and pip
```bash
cd <path_to_repo_fork>
python3 -m venv env
source env/bin/activate
pip install -r requirements.txt
pip install -e ./ # This will install pymdp as a local dev package
```

You should then be able to run tests locally with `pytest`
```bash
pytest test
```

## Authors

- Conor Heins [@conorheins](https://github.com/conorheins)
- Alexander Tschantz [@alec-tschantz](https://github.com/alec-tschantz)
- Beren Millidge [@BerenMillidge](https://github.com/BerenMillidge)
- Brennan Klein [@jkbren](https://github.com/jkbren)
- Arun Niranjan [@Arun-Niranjan](https://github.com/Arun-Niranjan)