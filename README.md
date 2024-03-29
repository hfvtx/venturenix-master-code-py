# Venturenix Master Code 2024
## Python Edition

This repo contains the code for Venturenix Master Code 2024.

### Code execution
The following instructions is applcable to MacOS terminal, Windows WSL and Linux. For specfic IDE please proceed accordingly.

In order to compete without problem, please ensure:

1. Have a virtual environment setup for the competition
```bash
python3 -m venv ~$USER/venv/mastercode2024
source ~$USER/venv/mastercode2024/bin/activate
```
2. Clone the repo to your local computer
```bash
git clone git@github.com:hfvtx/venturenix-master-code-py.git
```

3. Environment is properly setup
```bash
cd venturenix-master-code-py
pip3 install -r requirements.txt
```
Note: If you downloaded the source via http, the folder may have a different name such as `venturenix-master-code-py-main`

4. Try to run the code and see if it runs successfully
```bash
python3 main.py
```
*Output*
```
Running answers...
Benchmarking...

Reference
---------
Memory usage: 3231.6875 Mb
Average runtime: 4.44479
Benchmark CPU time: 2.9586
Final Score (reference only): 4971578.59052
```

### Code Submission
In order to submit your code, you need to download 2 files separately. __Please make sure to download both files into same folder containing the code. Do NOT rename the files.__
1. Personal private key

   Login to https://vtx-python-contest.softr.app/ by using the magic link sent to your personal e-mail box.  The filename should be `private_key`.
2. Service account json

   URL will be provided to the participants onsite.

The folder should look like this when you submit:
```bash
README.md
__pycache__
main.py
module.py
private_key
python-contest-submission.json
requirements.txt
submit.py
```

Once both files are in place, you could submit your code with the following command.
```bash
python3 submit.py
```
*Output*
```
Uploading files at Thu Mar  7 01:03:29 2024
```
> If you install new libraries into the environment, please ensure to update `requirements.txt` before submission or the scoring process will fail.
```bash
pip3 freeze > requirements.txt
```
__When time is up, the service account will be disabled and submission will fail. Please make sure to submit before time__

### Score
Your official score is available at: https://vtx-python-contest.softr.app/leaderboard-list