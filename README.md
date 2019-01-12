An easy way to get my public information by my GitHub nickname.

---

```
$ curl -s 'https://raw.githubusercontent.com/techtonik/public/master/public.json' | jq -r ".pubic_email"
techtonik@gmail.com
```
