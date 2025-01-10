# SDCP-Python

A Library for python to control SDCP devices like Elegoo's Resin Printers

## Setup
```
pip install -r requirements.txt
```

## Usage
After creating the virtual environment and installing the requirements, you can run ChitUI like this:
```
python main.py
```

## Configuration
Configuration is done via environment variables:
* `PORT` to set the HTTP port of the web interface (default: `54780`)
* `DEBUG` to enable debug logging, log colorization and code reloading (default: `False`)
