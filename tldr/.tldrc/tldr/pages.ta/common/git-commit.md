# git commit

> கோப்புகளை களஞ்சியத்திற்கு கமிட்செய்ய.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-commit>.

- ஒரு செய்தியுடன் களஞ்சியத்திற்கு அரங்குக் கோப்புகளை கமிட் செய்யுங்கள்:

`git commit -m "{{செய்தி}}"`

- அனைத்து மாற்றியமைக்கப்பட்ட கோப்புகளையும் தானாக நிலைநிறுத்து, செய்தியுடன் கமிட் செய்யுங்கள்:

`git commit -a -m "{{செய்தி}}"`

- கடைசி கட்டத்தை தற்போதைய நிலை மாற்றங்களுடன் கமிட் செய்யுங்கள்:

`git commit --amend`

- குறிப்பிட்ட (ஏற்கனவே அரங்கேற்றப்பட்ட) கோப்புகளை மட்டுமே கமிட் செய்யுங்கள்:

`git commit {{எனது/கோப்பு1க்கான/பாதை}} {{எனது/கோப்பு2க்கான/பாதை}}`
