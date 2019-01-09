An easy way to get my public information by my GitHub nickname.

---

```
$ curl -s 'https://raw.githubusercontent.com/techtonik/public/master/public.json' | jq -r ".email"
techtonik@gmail.com
```
