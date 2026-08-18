<div align="center">

# Hi there, I'm code002-2 👋

**Linux on Qualcomm Snapdragon · SBC / Tablet bring-up · Armbian**

I bring Linux mainline to smartphones and tablets that were only ever meant to run Android. Currently maintain the **[Xiaomi Pad 6S Pro (sheng)](https://github.com/armbian)** board enablement in Armbian, and build the tools that make running Linux on these devices practical.

</div>

---

## 🛠 What I do

- **Board BSP & bring-up** — UFS storage, Qualcomm ABL boot chain, DTBs, GPU/DP/audio, fast-charge authentication, boot-time initramfs tooling.
- **Armbian** — maintain the `xiaomi-sheng` board (sm8550), kernel branches, and a CI pipeline that turns them into installable images.
- **Mainline / semi-mainline kernels** — track SM8550 kernels, keep board support in sync with upstream churn.

See the [patch set for sheng](https://github.com/armbian/build/pull/9988) shipped in Armbian 26.08.

## 🔭 Currently

- Xiaomi Pad 6S Pro (sheng) support in Armbian — *merged*
- Exploring a boot menu for dual-boot (Android ⇄ Armbian)
- Building images for the board in CI

## 💻 Projects

| Project | Description |
|---|---|
| [`armbian-sheng`](https://github.com/code002-2/armbian-sheng) | Armbian build framework with Xiaomi Pad 6S Pro enablement |
| [`hmm`](https://github.com/code002-2/hmm) | GitHub Actions pipeline that builds sheng images |

## 📫 Contact

- GitHub: [code002-2](https://github.com/code002-2)
- Armbian forum: `code002` (Xiaomi Pad 6S Pro thread)

---

*Linux on the device that was designed to run Android — my favourite kind of problem.*