# Useless-Machine

A program for the dobot that cycles blocks between 2 conveyors.

## Setup

### Hardware

The hardware required is:

- 2 Dobot Magicians
- 2 Conveyors
- 2 Optic sensors
- 2 Color sensors

<!-- Insert schematic -->

### Software

First, download the script.
you can do this by downloading the zip or entering this in a terminal:

```bash
git clone https://github.com/JuliusDeBoer/Useless-Machine.git
```

After downloading everything you can start 2 instances of dobot studio and load both of the files and run them.

## Contributing

Simply send me a pull request and I will look into it.
Just make sure that you format it

### Formatting

Since dobot studio saves the files in 1 line you will need to format the files. I would recommend using [zpretty](https://github.com/collective/zpretty). You can install it using pip:

```bash
pip install zpretty
```

After installing zpretty simply run the following command:

```bash
zpretty -I alice.xml bob.xml
```
