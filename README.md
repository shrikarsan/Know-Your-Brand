# Know Your Brand

A simple program which gets Brand name as the input and genrate a pdf article with references based on it by using google search.

The article incliudes the following sub sections 
- History 
- Demographics 
- Social presence 
- Market activity 
- Reference Articles

## Setup

### API keys
We'll be using [OpenAI](https://platform.openai.com/docs/models/) to access ChatGPT model `gpt-3.5-turbo`. Be sure to create your account and have your credentials ready.

### Repository
```bash
git clone https://github.com/shrikarsan/Know-Your-Brand.git
git config --global user.name <GITHUB-USERNAME>
git config --global user.email <EMAIL-ADDRESS>
```
### Environment

Then set up the environment correctly by specifying the values in your `.env` file,
and installing the dependencies:

```bash
pip install --user -r requirements.txt
export PYTHONPATH=$PYTHONPATH:$PWD
```

### Credentials
```bash
touch .env

# Add environment variables to .env
OPENAI_API_BASE="https://api.openai.com/v1"
OPENAI_API_KEY=""  # https://platform.openai.com/account/api-keys
GOOGLE_CSE_ID=""
GOOGLE_API_KEY=""

source .env
```

Now we're ready to go through the [know-your-brand.ipynb](know-your-brand.ipynb) interactive notebook to develop and run our application!

An article with **CocaCola** Brand is shown as example.