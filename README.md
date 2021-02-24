# :cow: TH Masterclass 2021 :cow: : A simple tutorial on data impact on algorithm generalization based on cows

:cow: Based on `jupyter notebooks`, the aim of this small project is to provide an insight into how choices on data can impact how technology performs in the real world, as a springboard for discussion on more complex data.

No previous coding experience is required - you just need the ability to click enter on the cells in the notebook, which runs in your browser! All data and tools are open-source (free). :cow:

## Configuring your laptop from scratch

If you have `git` installed and configured, skip these steps.

### Windows
If you don't have a git client, get it set up on your laptop by downloading the software [here](https://git-scm.com/download/win) and installing it.

### Mac/Linux
If you don't have homebrew installed, you'll need to install it on your computer by downloading the software [here](https://brew.sh/) and installing it.

Then, you can open a `terminal` and type:
```bash
brew install git
```

## Conda 

Go to the [miniconda](https://docs.conda.io/en/latest/miniconda.html) website, and download the appropriate install for your operating system (Windows, Mac, Linux), and follow installation instructions.

## Create a conda env
Once `conda` has been installed, we have to create an environment to run our experiments. For windows systems, use the `git bash` shell for the following commands, and for Mac use `terminal`.

Create an env:
```bash
conda create --name th-cow-classifier python=3.6
```

Enter the env:
```bash
conda activate th-cow-classifier
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Your environment is now set up.

# Run the notebook
From your environment, run:

```bash
jupyter notebook
```

This will open the tutorial in your browser and you'll be able to follow along. Have fun!

:cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: :cow: