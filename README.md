# try-eda

```
AAP_URL=
AAP_TOKEN=
ansible-rulebook --rulebook rulebooks/hello.yml -i inventory.yml --verbose --controller-url $AAP_URL --controller-token $AAP_TOKEN --controller-ssl-verify no --hot-reload -e vars.yml

curl -X POST localhost:5000/aa -H "Content-Type: application/json" --data '{"message":"Ansible is super cool!"}'

date >> eda.txt
python -m http.server
# rm eda.txt
```
