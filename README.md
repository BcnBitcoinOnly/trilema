## 1ma fork of Trilema archive

### Branches

* `main`: original archive from 2021 made by [@BullishNode](https://github.com/BullishNode)
* `master`: extra commits to clean up duplicate content and serve the site nicely with Caddy and Cloudflare Pages

### Cloudflare Mirror

Available at: [trilema.bitcoinbarcelona.xyz](https://trilema.bitcoinbarcelona.xyz)

> [!WARNING]
> Use the Tor Browser or host your own private copy of the site for better privacy.

The Cloudflare project is configured with `xargs -r rm -rf < _ignores; rm -f _ignores` as the build command.

Files larger than 25MB need to be added to the _ignores file because Cloudflare Page's free tier rejects them.

### Run Locally

#### Docker

```shell
docker compose up -d
```

Browse it at http://localhost

#### Host a private copy

Install Caddy on your server and use the Caddyfile provided with this repo,
adjusting as needed.


### Known lost resources

* /wp-content/themes/trilema/ad2.png
* /wp-content/themes/trilema/images/bg_apr.jpg
* /wp-content/themes/trilema/images/bg_july.jpg
* /wp-content/themes/trilema/images/bg_oct.jpg
* /wp-content/uploads/2015/12/bitbet-intake-nov-2015.png
* /wp-content/uploads/2015/12/juan-iliesco-560x746.jpg
* /wp-content/uploads/2015/12/juan-iliesco.jpg
* /wp-content/uploads/2015/12/tumblr_njeogaq6wf1u5qv2bo1_1280.jpg
* /wp-content/uploads/2019/10/schlob-6.jpg
* /wp-content/uploads/tlpimages/images/

Original README.md follows:

---

# trilema
Archive of Trilema.com

In Memoriam Mircea Popescu, the original Toxic Bitcoin Maximalist.

## Contributing

This snapshot of Trilema.com was made on June 27 2021. Shortly after the backup was made, the Trilema.com website became unresponsive. We do not know if the backup of the website was completed sucessfully in its entirety. If you are aware of or possess missing content, please submit a PR.
