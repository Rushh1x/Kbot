# The Amazing Automatic Kahoot Bot (KBSot)
### *now with functional code*
People have made bots and things for kahoot in the past, but this is
a new and improved edition that actually does
everything for you. This one actually answers the questions, unlike
some other tools and spammers. 

## Getting Started

- [ ] Make Kahoot Account
- [ ] Install Python3
  - On MacOS, Install [Homebrew](https://brew.sh/), then install Python.
    - `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
    - `brew install python`
- [ ] Clone this project
  - `https://github.com/Rushh1x/Kbot.git`
- [ ] Install Dependencies
  - `python3 -m pip install -r requirements.txt`
- [ ] Run Program
  - `python3 kbot`

## Program arguments

```
python3 kbot
  --email XYZ@gmail.com 
  --password XYZ
```

Please open a pull request or issue if you would like more functionality.

## How does it work?

Intercepts and pretends to be a kahoot client. After receiving quiz name from host, looks up answers for quiz and uses them.

## Caveats

Does not work when:

+ Kahoot is private
+ Answers are randomized
+ Questions are randomized

This is because this program uses the original question order and answer order, so if these are modified the wrong answer will be clicked.
## Questions?
 + please open an issue
 
## Contributors

* [rush](https://github.com/Rushh1x) - Main programming
