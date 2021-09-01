# Powercalc measure tooling

This package contains everything you need to automatically take measurements of lights to contribute to this repository.

## Setup

**Prerequisites:**
- Make sure you have Python 3 running on your system. version 3.8 or higher is advised.

Setup requirements for the script. It is advised to run in a virtual environment.
```
cd utils/measure_v2
python3 -m venv measure
source measure/bin/activate
pip install -r requirements.txt
```

When this is not working on your machine (i.e. windows) just install globally.
```
cd utils/measure_v2
pip install -r requirements.txt
```

Copy the `.env.dist` file to `.env` and modify the configuration parameters according to your needs.
You will need to select a `POWER_METER` and `LIGHT_CONTROLLER`

## Run

```
python3 measure.py
```

The script will ask you a few questions, than proceed taking measurements.

@TODO Add some information about duration of measurements.