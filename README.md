<p align="left">
    <a href="https://github.com/orgs/leraniode/repositories?q=x">
        <img src="https://raw.githubusercontent.com/leraniode/.github/main/assets/images/xbrandimage.png" width="600" />
    </a>
</p>

# X

> Experimental and Development Packages for Leraniode/ projects

[![part of leraniode](https://raw.githubusercontent.com/leraniode/.github/main/assets/badges/partofleraniode.svg)](https://github.com/leraniode)
[![experimental-leraniode](https://raw.githubusercontent.com/leraniode/.github/main/assets/badges/experimentalleraniode.svg)](https://github.com/orgs/leraniode/repositories?q=x)

---

## xgo

[![license](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Status](https://img.shields.io/badge/status-experimental-orange)]()

Experimental Go libraries used for development and testing in Projects under [Leraniode](https://github.com/leraniode).

Packages in this repository are pre-stable. APIs may break between commits.
Each package graduates to its own repository once the algebra is proven,
integrations are validated, and the API is stable.

---


## Ecosystem

All projects under **xgo** are:
- Part of the **Experimental Leraniode** ecosystem
- Maintained or curated by Leraniode

---

### Packages

- [`centrix`](./centrix): 
Sparse signal mathematics library. Defines the primitives, algebra, and field
dynamics for reasoning and generation systems.


---

### Structure

Each package is an independent Go module with its own `go.mod`.
Use a `go.work` file locally to work across packages simultaneously:

```bash
go work init
go work use ./centrix
```

The `go.work` file is gitignored — it is a local development tool, not part
of the repository.

---

## Your Thoughts Matter

> [!NOTE]
> Leraniode thrives on community ideas and experimentation.
> So your contribution is welcomed!

If you have suggestions, feedback, or ideas for new experimental packages or improvements, join the discussion:

- 💬 [Leraniode Discussions](https://github.com/leraniode/xgo/discussions)

---

<p align="left">
x-py • Experimental Leraniode • Part of Leraniode
</p>

<img
  align="left"
  src="https://raw.githubusercontent.com/leraniode/.github/main/assets/footer/leraniodeproductbrandimage.png"
  alt="Leraniode"
  width="400"
  style="border-radius: 15px;"
/>