# README

## workflow

Get working rambo setup, then add lastpass tokens to grains file and then run rambo up.


You can enable git push/pull by running

rambo scp ~/.ssh/id_rsa :/home/vagrant/.ssh/id_rsa

rambo scp ~/.ssh/id_rsa.pub :/home/vagrant/.ssh/id_rsa.pub

rambo ssh

cd inflation-app

python app.py

sudo chown vagrant inflation-app -R

bash testing/utils/forward_8080_to_80.sh
