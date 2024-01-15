sudo apt install python3
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py
python3 -m pip install openai
python3 -m venv openai-env
sudo apt install python3.8-venv
python3 -m venv openai-env
source openai-env/bin/activate
pip install --upgrade openai

export OPENAI_API_KEY='your-api-key-here'
