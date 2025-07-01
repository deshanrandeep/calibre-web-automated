<hr />

<p align="center">
  <em>📚 Bestow upon us a ⭐️ if this humble project has brought order to your literary affairs.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Install%20Prospects-Excellent-blue?logo=docker" alt="Install Prospects" />
  <img src="https://img.shields.io/github/license/scottgigawatt/calibre-web-automated?label=Entailment-Free%20License&color=blue" alt="License" />
  <img src="https://img.shields.io/github/last-commit/scottgigawatt/calibre-web-automated?label=Most%20Recent%20Correspondence&logo=git" alt="Last Commit" />
  <img src="https://img.shields.io/github/repo-size/scottgigawatt/calibre-web-automated?label=Voluminous%20Assets" alt="Repo Size" />
  <img src="https://img.shields.io/badge/Tested%20in%20Society-Synology%20%7C%20macOS-blue" alt="Shelf-Tested" />
</p>

<hr />

# Calibre Web Automated 📚🧙‍♂️

It is a truth universally acknowledged, that a bibliophile in possession of a vast collection of ebooks, must be in want of an elegant method of organization. Thus, dear reader, we present to you **Calibre Web Automated**—a Docker Compose deployment most genteel and efficient, suitable for even the most refined Synology parlours.

## A Brief Introduction ✨

> 🎩📖 _A disorderly library is, to a discerning mind, scarcely to be borne._

This compose arrangement provides for the installation of Calibre Web Automated, a system of such grace and capability that it may tame even the wildest EPUB collection. Whether one's library comprises dusty Gothic romances, scandalous fanfic, or scholarly treatises, this system brings civility and order to every volume.

Peruse the Docker Compose manuscript here:

- 📄 [View docker-compose.yml](./docker-compose.yml)

Our profound gratitude to the ever-illuminating [Lixandru Marius Bogdan](https://github.com/mariushosting) 🔮📖, whose treatise—[this guide](https://mariushosting.com/how-to-install-calibre-web-automated-on-your-synology-nas)—served as our lantern in the darkened stacks.

## The Contents of Our Library 🛠️

A modest index of the marvels you shall summon:

| Apparatus                    | Description                                                                 | Further Reading                                         |
|------------------------------|-----------------------------------------------------------------------------|---------------------------------------------------------|
| **Calibre Web Automated** 📘 | A mechanism most wondrous for the curation, ingestion, and exhibition of tomes. | [GitHub](https://github.com/crocodilestick/calibre-web-automated) |

> [!NOTE]
> 📚 Though many have endeavoured to automate the cataloguing of ebooks, no solution yet proves entirely complete. Tools like Readarr have fallen into disrepair, and thus, a degree of manual stewardship—guided by this project’s automation—is presently the most reliable path for the attentive reader.

## Commencement of Deployment 🚀

### 🛠️ Acquiring the Repository

To initiate this genteel apparatus, one must first acquire the repository, as one might retrieve a cherished tome from a locked cabinet:

```sh
git clone https://github.com/scottgigawatt/calibre-web-automated.git /volume1/docker/calibre-web-automated
```

> [!NOTE]
> 🧾 Be thou upon Synology 📦, macOS 🍎, Linux 🐧, or even a particularly enchanted slab of stone—adjust thy path as wisdom dictates.

### 🧪 Concocting the Proper Environment

No alchemical solution succeeds without its precise reagents. Begin, if you please, by copying the sample `.env` manuscript:

- 📄 [View example.env](example.env)

```sh
cp example.env .env

# Adjust its contents to suit thy estate
vim .env
```

> [!TIP]
> Prefer to dictate your spells from the command line? Cast overrides like so:
>
> ```bash
> CWA_TAG="latest" docker compose up -d
> ```

### 📚 A Note of Caution and Preparation

> [!IMPORTANT]
> 🧙 The wise bibliophile studies the preface. Do not skip the setup guide, lest your library descend into chaos.

Consult the [Setup Guide](./SETUP.md), which details rites and rituals for Synology deployment, container conjuring, and the warding of firewalls.

Of particular interest:

- 🌐📖 [Docker Networking](./SETUP.md#configuring-docker-networking-)
- 🧱⚙️ [Synology Provisions](./SETUP.md#synology-configuration-)
  - 🔥🛡️ [Firewall Incantations](./SETUP.md#updating-firewall-settings-)
  - 📦🚀 [Container Manager Rituals](./SETUP.md#deploying-with-container-manager-)

To disregard this guidance would be most imprudent.

## Suitable Reading Rooms 🧵

This composition has been favourably tested upon the DS1522+ and DS916+ (DSM 7.2), but it performs admirably upon any host capable of sustaining Docker's arcane machinery.

## License of Gentlefolk 📖

This project, like any well-loved volume, is shared under the Apache 2 License—open shelves, open code.

---

```
        (
         )     🖋️ *Whitt & Folio*
      (   )    "To read without order is to dine without table or chair."
       (_)
        ||
       ====     ~ A genteel solution for the modern bibliophile ~
       ||||
       ||||
```

Pull requests, new spells, and annotated margins welcome.
Yours in service of the Library,
The Maintainers
