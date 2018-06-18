# AIY Projects

<img src="https://aiyprojects.withgoogle.com/static/images/icons/aiy-circular-logo.svg" width="40%">

This repository contains an easy-to-use API for the AIY Vision Kit and
AIY Voice Kit.
You can use it for face detection and object recognition, or use it to create
voice commands with simple while loops - have a look at the
[demos](https://github.com/google/aiyprojects-raspbian/tree/aiyprojects/src/examples).
Documentation is at the [AIY Projects site](https://aiyprojects.withgoogle.com).

If you're using Raspbian instead of Google's provided image, read
[HACKING.md](HACKING.md) for information on getting started.

For returning users:
The code for all AIY kits is in the `aiyprojects` branch, and is included in
images starting with aiyprojects-2017-12-18.img. The previous `voicekit` branch
contains code just for the Voice Kit, and the `master` branch contains the
original, deprecated Voice Recognizer demo.

## Support

If you're having trouble assembling your kit or running the demos,
try the [AIY Forums](https://www.raspberrypi.org/forums/viewforum.php?f=114).

If you've found a bug in the AIY API or demos, you can look at the
[known issues](https://github.com/google/aiyprojects-raspbian/issues) or create
a new one, or even fix it yourself and send us a pull request.

If you've found a problem with the Assistant (for example, crashes in the
library or incorrect responses), you can try
[the G+ community](https://plus.google.com/communities/117537996116836200696),
[Stack Overflow](https://stackoverflow.com/questions/tagged/google-assistant-sdk),
or [the assistant-sdk-python repo](https://github.com/googlesamples/assistant-sdk-python/).

If you've had a problem after updating the source code, try downloading the
latest AIY image from the website, or alternatively run the following commands
in the dev terminal:

```
rm -r env
./scripts/install-deps.sh
```

## Contributions

We'd love to accept your patches and contributions to this project. There are
just a few small guidelines you need to follow.

### Scope of contributions

This project consists of the support libraries (audio, gRPC, etc) required for AIY Projects, as well as simple examples to experiment with and build upon.

Please limit pull requests to bug fixes or improvements to code or documentation clarity.
We're not accepting pull requests that add new commands to keep this project as simple as possible.
If you've added new commands and you'd like to publish your fork for others to use, you can post on [hackster.io](https://www.hackster.io/) or other channels.

### Contributor License Agreement

Contributions to this project must be accompanied by a Contributor License
Agreement. You (or your employer) retain the copyright to your contribution,
this simply gives us permission to use and redistribute your contributions as
part of the project. Head over to <https://cla.developers.google.com/> to see
your current agreements on file or to sign a new one.

You generally only need to submit a CLA once, so if you've already submitted one
(even if it was for a different project), you probably don't need to do it
again.

### Code reviews

All submissions, including submissions by project members, require review. We
use GitHub pull requests for this purpose. Consult [GitHub Help] for more
information on using pull requests.


[GitHub Help]: https://help.github.com/articles/about-pull-requests/
