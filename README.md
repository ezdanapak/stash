# stash — ჩემი საცავი

ბმულები, ჯგუფები და საინტერესო მასალები ერთ ადგილას. მასალა `docs/`-შია, საიტი კი [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)-ით იწყობა.

## სად რა არის

| ფაილი | რა დევს |
| --- | --- |
| [docs/inbox.md](docs/inbox.md) | სწრაფი ჩანაწერები: ჯერ აქ ჩაწერე, მერე დაალაგე |
| [docs/links.md](docs/links.md) | ცალკეული ბმულები თემების მიხედვით |
| [docs/groups.md](docs/groups.md) | ჯგუფები, არხები, საზოგადოებები |
| [docs/ai/](docs/ai/) | AI, Claude, პრომპტები |

## საიტის გაშვება ლოკალურად

```bash
python3 -m venv .venv && .venv/bin/pip install -r requirements.txt
.venv/bin/mkdocs serve
```

მერე გახსენი <http://127.0.0.1:8000>. ახალი გვერდი `mkdocs.yml`-ის `nav`-შიც უნდა დაამატო.
