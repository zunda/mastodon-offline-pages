# mastodon-offline-pages
Pages that show error or maintenance on a Mastodon instance

## Hacking
### Fetch templates from a running Mastodon instance
```
$ host=<FQDN for your mastodon instance>
$ wget -r -k -np -nH -P public --wait=2 https://$host/500.html
$ rm -f public/robots.txt
```

Rename and edit to remove the fingerprints.

## LICENSE
Following files are copied from [tootsuite/mastodon](https://github.com/tootsuite/mastodon) Copyright (C) 2016-2018 Eugen Rochko & other Mastodon contributor under the GNU Affero General Public License.

- public/500.html
- public/oops.gif
- public/packs/Montserrat-Medium-5f797490f806b3b229299f0a66de89c9.ttf
- public/packs/Montserrat-Regular-080422d4c1328f3407818d25c86cce51.woff2
- public/packs/Montserrat-Regular-6a18f75e59e23e7f23b8a4ef70d748cd.ttf
- public/packs/Montserrat-Regular-b0322f2faed575161a052b5af953251a.woff
- public/packs/common-95a9b8d67061f05d05ea.css
- public/packs/default-8de8b360d8d109f044fa.css
- public/packs/elephant_ui_disappointed-8864342480c3612e3061702851d3a798.svg
- public/packs/elephant_ui_greeting-475430963d0b00fe82b07b17857ebf6c.svg
- public/packs/elephant_ui_plane-e3f2d57c12c376e189c274cbe81af8dd.svg
- public/packs/elephant_ui_working-2e653cc278c2ac871c23aeb10de1c0e2.svg
- public/packs/fontawesome-webfont-674f50d287a8c48dc19ba404d20fe713.eot
- public/packs/fontawesome-webfont-674f50d287a8c48dc19ba404d20fe713.eot?
- public/packs/fontawesome-webfont-912ec66d7572ff821749319396470bde.svg
- public/packs/fontawesome-webfont-af7ae505a9eed503f8b8e6982036873e.woff2
- public/packs/fontawesome-webfont-b06871f281fee6b241d60582ae9369b9.ttf
- public/packs/fontawesome-webfont-fee66e712a8a08eef5805a46892932ad.woff
- public/packs/reticle-6490ecbb61185e86e62dca0845cf2dcf.png
- public/packs/roboto-bold-webfont-4cbd1966fc397282fa35d69070782b80.svg
- public/packs/roboto-bold-webfont-5bacc29257521cc73732f2597cc19c4b.ttf
- public/packs/roboto-bold-webfont-df0f5fd966b99c0f503ae50c064fbba8.woff
- public/packs/roboto-bold-webfont-f633cb5c651ba4d50791e1adf55d3c18.woff2
- public/packs/roboto-italic-webfont-4c71bd4a88468ea62f92e55cb4e33aef.ttf
- public/packs/roboto-italic-webfont-50efdad8c62f5f279e3f4f1f63a4f9bc.woff2
- public/packs/roboto-italic-webfont-927fdbf83b347742d39f0b00f3cfa99a.woff
- public/packs/roboto-italic-webfont-d88a9e8476fabedea3b87fd0ba2df3b3.svg
- public/packs/roboto-medium-webfont-6484794cd05bbf97f3f0c730cec21665.woff
- public/packs/roboto-medium-webfont-69c55fc2fe77d38934ea98dc31642ce6.woff2
- public/packs/roboto-medium-webfont-7f0e4c7727a4bc5f37d95d804c6e0348.ttf
- public/packs/roboto-medium-webfont-f407ec033f15172c3c4acf75608dd11d.svg
- public/packs/roboto-regular-webfont-3ec24f953ed5e859a6402cb3c030ea8b.woff2
- public/packs/roboto-regular-webfont-42a434b9f3c8c7a57b83488483b2d08e.ttf
- public/packs/roboto-regular-webfont-77dc6a0145954a963b95d30773543105.svg
- public/packs/roboto-regular-webfont-b06ad091cf548c38401f3e5883cb36a2.woff
- public/packs/robotomono-regular-webfont-09e0ef66c9dee2fa2689f6e5f2437670.woff
- public/packs/robotomono-regular-webfont-0ba95b3b2370e6bf1dcdb20aa3a54ff2.ttf
- public/packs/robotomono-regular-webfont-51e9ccf8c829f4894a7e5a0883e864fc.svg
- public/packs/robotomono-regular-webfont-6c1ce30b90ee993b22618ec489585594.woff2
- public/packs/void-4c8270c17facce6d53726a2ebb9745f2.png
