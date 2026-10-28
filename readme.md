cd "/home/foko-junior/Ecole M2/Cours/test et validation logiciel/facturecloud"
rm -rf .venv
python3 -m venv .venv
source .venv/bin/activate
pip install -r api-factures/requirements.txt -r service-calcul/requirements.txt -r service-notifications/requirements.txt
