# About the code

The repository contains programs to recommend users on the best flights available between two given airports. Idea is that users can enter all the reqquirements in plain text and the system should be able to fetch the recommended flights based on that.

## How to run the code

First clone the repository.

```bash 
git clone https://github.com/flight-recommendation
```

Next create virtual environment.

```bash
virtualenv .venv
```

Now activate the virtual environment.

```bash
source .venv/bin/activate
```

Install the required dependencies.

```bash
pip install -r requirements.txt
```
Next step would be to create env variables. 

```bash
mv .env.example .env
```
Enter the necessary variables there.

Not you can run the ipynb files. 