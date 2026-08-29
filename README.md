# Awesome UEFI Security with stars

This repository contains a collection of UEFI/BIOS security materials. Collected my own, not comprehensive. Feel free to PR.

* [Awesome UEFI Security ](#awesome-uefi-security-)
  * [CTF Challenges](#ctf-challenges)
  * [Documentations :book:](#documentations-book)
  * [Development :computer:](#development-computer)
  * [Bootkits :bomb:](#bootkits-bomb)
  * [Tools :hammer:](#tools-hammer)
  * [Vulnerabilities & Exploits :mag\_right:](#vulnerabilities--exploits-mag_right)
  * [Talks :speaker:](#talks-speaker)
  * [Blogs :newspaper:](#blogs-newspaper)
  * [Papers :page\_with\_curl:](#papers-page_with_curl)
  * [Training & Courses :beginner:](#training--courses-beginner)

## CTF-Challenges

* [DVUEFI](https://github.com/hacking-support/DVUEFI) ⭐ 307 | 🐛 2 | 🌐 C++ | 📅 2024-09-09
* [UIUCTF-2022 SMM Cow Say 1](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/systems/smm_cowsay_1) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2022-08-09
* [UIUCTF-2022 SMM Cow Say 2](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/systems/smm_cowsay_2) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2022-08-09
* [UIUCTF-2022 SMM Cow Say 3](https://github.com/sigpwny/UIUCTF-2022-Public/tree/main/systems/smm_cowsay_3) ⭐ 32 | 🐛 0 | 🌐 Python | 📅 2022-08-09
* [D^3CTF-2022-pwn-d3guard](https://github.com/yikesoftware/d3ctf-2022-pwn-d3guard) ⭐ 14 | 🐛 1 | 🌐 Python | 📅 2022-03-09
* [corCTF 2023 smm-diary](https://2023.cor.team/challs)
* [Dubhe CTF 2024 ToySMM](https://dubhectf2024.xctf.org.cn/)

## Documentations :book:

* [UEFI Forum](https://uefi.org/)
* [UEFI Specification v2.10](https://uefi.org/sites/default/files/resources/UEFI_Spec_2_10_Aug29.pdf)
* [UEFI Platform Initialization Specification v1.7a](https://uefi.org/sites/default/files/resources/PI_Spec_1_7_A_final_May1.pdf)
* [UEFI Shell Specification V2.2](http://www.uefi.org/sites/default/files/resources/UEFI_Shell_2_2.pdf)
* [UEFI Platform Initialization Distribution Packaging Specification v1.1](http://www.uefi.org/sites/default/files/resources/Dist_Package_Spec_1_1.pdf)
* [ACPI Specification v6.5](https://uefi.org/sites/default/files/resources/ACPI_Spec_6_5_Aug29.pdf)

## Development :computer:

* [uefi-rs](https://github.com/rust-osdev/uefi-rs) ⭐ 1,646 | 🐛 33 | 🌐 Rust | 📅 2026-08-27
* [UEFI-Lessons](https://github.com/Kostr/UEFI-Lessons) ⭐ 366 | 🐛 1 | 🌐 C | 📅 2024-03-05
* [arch-secure-boot](https://github.com/maximbaz/arch-secure-boot) ⭐ 146 | 🐛 3 | 🌐 Shell | 📅 2024-07-18
* [edk2-libc](https://github.com/tianocore/edk2-libc) ⭐ 135 | 🐛 23 | 🌐 Python | 📅 2026-08-11
* [edk2-pytool-library](https://github.com/tianocore/edk2-pytool-library) ⭐ 67 | 🐛 11 | 🌐 Python | 📅 2026-08-24
* [EDK II](https://github.com/edk2/edk2)
* [EDK II Module Write Guide](https://tianocore-docs.github.io/edk2-ModuleWriteGuide)

Some interesting projects

* [mitnal](https://github.com/arata-nvm/mitnal) ⭐ 528 | 🐛 1 | 🌐 C | 📅 2022-01-31
* [uefi-paint](https://github.com/nrdmn/uefi-paint) ⭐ 50 | 🐛 0 | 🌐 Zig | 📅 2019-09-20

## Bootkits :bomb:

ATT\&CK [Attack Vector](https://attack.mitre.org/techniques/T1542/003/)

|    Time   |                                                         Name                                                        |
| :-------: | :-----------------------------------------------------------------------------------------------------------------: |
| Nov. 2024 |      [Bootkitty](https://www.welivesecurity.com/en/eset-research/bootkitty-analyzing-first-uefi-bootkit-linux/)     |
| Oct. 2022 |           [BlackLotus](https://www.welivesecurity.com/2023/03/01/blacklotus-uefi-bootkit-myth-confirmed/)           |
| Jul. 2022 |                  [CosmicStrand](https://securelist.com/cosmicstrand-uefi-firmware-rootkit/106973/)                  |
| Jan. 2022 |                [MoonBounce](https://securelist.com/moonbounce-the-dark-side-of-uefi-firmware/105468/)               |
| Oct. 2021 |     [Especter](https://www.welivesecurity.com/2021/10/05/uefi-threats-moving-esp-introducing-especter-bootkit/)     |
| Sep. 2021 |                           [FinSpy](https://securelist.com/finspy-unseen-findings/104322/)                           |
| Dec. 2020 | [Trickbot](https://eclypsium.com/wp-content/uploads/2020/12/TrickBot-Now-Offers-TrickBoot-Persist-Brick-Profit.pdf) |
| Oct. 2020 |                           [MosaicRegressor](https://securelist.com/mosaicregressor/98849/)                          |
|    2018   |    [LoJax](https://www.welivesecurity.com/2018/09/27/lojax-first-uefi-rootkit-found-wild-courtesy-sednit-group/)    |

<!-- [iLOBleed](https://threats.amnpardaz.com/en/2021/12/28/implant-arm-ilobleed-a/)
[iLOBleed PDF Version](https://threats.amnpardaz.com/en/wp-content/uploads/sites/5/2021/12/Implant.ARM_.iLOBleed.a-en.pdf) -->

Bootkits related repositories:

* [SmmBackdoor](https://github.com/Cr4sh/SmmBackdoor) ⭐ 633 | 🐛 0 | 🌐 C | 📅 2023-10-09
* [umap](https://github.com/btbd/umap) ⭐ 602 | 🐛 7 | 🌐 C | 📅 2024-01-01
* [UEFI-Bootkit](https://github.com/ajkhoury/UEFI-Bootkit) ⭐ 528 | 🐛 0 | 🌐 C | 📅 2019-08-29
* [PeiBackdoor](https://github.com/Cr4sh/PeiBackdoor) ⭐ 232 | 🐛 0 | 🌐 C | 📅 2021-05-01
* [LoJax](https://github.com/loneicewolf/LOJAX) ⭐ 38 | 🐛 1 | 📅 2023-03-09
* [bootlicker](https://github.com/realoriginal/bootlicker)

## Tools :hammer:

* [PciLeech](https://github.com/ufrisk/pcileech) ⭐ 7,899 | 🐛 9 | 🌐 C | 📅 2026-07-25: PciLeech supports DMA attacks against UEFI, and it contains a mode can hook UEFI Runtime Services and print some chars.
* [qiling](https://github.com/qilingframework/qiling) ⭐ 6,079 | 🐛 122 | 🌐 Python | 📅 2026-07-22: Qiling has an EFI mode, which can partially emulate UEFI binary files.
* [UEFITool](https://github.com/LongSoft/UEFITool) ⭐ 5,644 | 🐛 23 | 🌐 C | 📅 2026-07-29: Tool for parsing and extracting UEFI firmware images.
* [Chipsec](https://github.com/chipsec/chipsec) ⭐ 3,296 | 🐛 44 | 🌐 Python | 📅 2026-08-27: The most commonly used tool for extracting UEFI firmware and exploiting UEFI vulnerabilities.
* [EfiGuard](https://github.com/Mattiwatti/EfiGuard) ⭐ 2,522 | 🐛 20 | 🌐 C++ | 📅 2026-06-16
* [uefi-rs](https://github.com/rust-osdev/uefi-rs) ⭐ 1,646 | 🐛 33 | 🌐 Rust | 📅 2026-08-27: A rust wrapper for UEFI. You can built UEFI applications and vulnerabilities PoCs easily with this library.
* [innoextract](https://github.com/dscharrer/innoextract) ⭐ 1,348 | 🐛 72 | 🌐 C++ | 📅 2025-02-06: A tool to unpack installers created by Inno Setup
* [efiXplorer](https://github.com/binarly-io/efiXplorer) ⭐ 1,126 | 🐛 0 | 🌐 C++ | 📅 2026-08-20: IDA Pro plugin, the best plugin for analyzing UEFI binaries for now.
* [BIOSUtiities](https://github.com/platomav/BIOSUtilities) ⭐ 1,080 | 🐛 3 | 🌐 Python | 📅 2025-07-01: A lot of scripts to parse and extract UEFI firmware images directly from exe files.
* [uefi-firmware-parser](https://github.com/theopolis/uefi-firmware-parser) ⭐ 921 | 🐛 12 | 🌐 Python | 📅 2026-06-04: Library for parsing UEFI firmware images.
* [efi-memory](https://github.com/SamuelTulach/efi-memory) ⚠️ Archived
* [ghidra-firmware-utils](https://github.com/al3xtjames/ghidra-firmware-utils) ⭐ 491 | 🐛 11 | 🌐 Java | 📅 2026-07-29
* [dropWPBT](https://github.com/Jamesits/dropWPBT) ⭐ 448 | 🐛 1 | 🌐 C | 📅 2020-05-22
* [efiSeek](https://github.com/DSecurity/efiSeek) ⭐ 405 | 🐛 12 | 🌐 Java | 📅 2024-06-02: A Ghidra plugin for UEFI binaries analyzing.
* [fiano](https://github.com/linuxboot/fiano) ⭐ 372 | 🐛 60 | 🌐 Go | 📅 2026-05-14
* [uefi-retool](https://github.com/yeggor/uefi_retool) ⚠️ Archived
* [tsffs](https://github.com/intel/tsffs) ⭐ 331 | 🐛 32 | 🌐 Rust | 📅 2026-08-13: A snapshotting, coverage-guided fuzzer for software (UEFI, Kernel, firmware, BIOS) built on SIMICS, released by Intel.
* [fwexpl](https://github.com/Cr4sh/fwexpl) ⭐ 263 | 🐛 0 | 🌐 C++ | 📅 2022-05-13
* [FwHunt](https://github.com/binarly-io/fwhunt) ⭐ 248 | 🐛 1 | 📅 2024-03-12
* [fwhunt-scan](https://github.com/binarly-io/fwhunt-scan) ⭐ 243 | 🐛 0 | 🌐 Python | 📅 2025-05-02
* [VBiosFinder](https://github.com/coderobe/VBiosFinder) ⭐ 155 | 🐛 30 | 🌐 Ruby | 📅 2023-11-05
* [efi\_fuzz](https://github.com/Sentinel-One/efi_fuzz) ⚠️ Archived: A coverage-guided emulator-based NVRAM fuzzer for UEFI (based on qiling).
* [UefiVarMonitor](https://github.com/tandasat/UefiVarMonitor) ⭐ 146 | 🐛 0 | 🌐 C | 📅 2020-10-09
* [kraft\_dinner](https://github.com/tandasat/kraft_dinner) ⭐ 114 | 🐛 0 | 🌐 C | 📅 2020-12-24
* [brick](https://github.com/Sentinel-One/brick) ⚠️ Archived: IDA Pro plugin, a static vulnerability scanner, support several types of vulnerabilities.
* [efi\_dxe\_emulator](https://github.com/assafcarlsbad/efi_dxe_emulator) ⭐ 88 | 🐛 3 | 🌐 C | 📅 2020-04-29: A simple emulator for UEFI DXE files.
* [smram\_parse](https://github.com/Cr4sh/smram_parse) ⭐ 83 | 🐛 2 | 🌐 Python | 📅 2024-08-09
* [ebvm](https://github.com/yabits/ebcvm) ⭐ 82 | 🐛 0 | 🌐 C | 📅 2023-01-29
* [efi-resolver](https://github.com/Vector35/efi-resolver) ⚠️ Archived: Official UEFI plugin for Binary Ninja; it supports type propogation, which is really cool, and it starts supporting PEI files now.
* [UEFI-SecureBoot-SignTool](https://github.com/aneesh-neelam/UEFI-SecureBoot-SignTool) ⭐ 31 | 🐛 2 | 🌐 Shell | 📅 2019-10-24
* [python-uefivars](https://github.com/awslabs/python-uefivars) ⭐ 28 | 🐛 3 | 🌐 Python | 📅 2024-09-13: A python tool to inspect UEFI variables (but it cannot take firmware images as input).
* [efi-inspector](https://github.com/zznop/efi-inspector) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-02-28: A Binary Ninja plugin for parsing UEFI firmware images.
* [LVFS](https://fwupd.org)
* [Voyager](https://git.back.engineering/_xeroxz/voyager)
* [bob\_efi\_fuzzer](https://github.com/HO-9/bob_efi_fuzzer)

## Vulnerabilities & Exploits :mag\_right:

* [Super-UEFIinSecureBoot-Disk](https://github.com/ValdikSS/Super-UEFIinSecureBoot-Disk) ⭐ 841 | 🐛 8 | 📅 2022-06-20
* [ThinkPwn](https://github.com/Cr4sh/ThinkPwn) ⭐ 707 | 🐛 0 | 🌐 C | 📅 2022-05-13
* [CVE-2022-21894](https://github.com/Wack0/CVE-2022-21894) ⭐ 353 | 🐛 4 | 🌐 C | 📅 2023-09-27
* [Vulnerability-REsearch](https://github.com/binarly-io/Vulnerability-REsearch) ⭐ 195 | 🐛 1 | 🌐 Python | 📅 2026-08-06: Vulnerabilities found by Binarly-IO, really a lot.
* [SmmExploit](https://github.com/tandasat/SmmExploit) ⭐ 149 | 🐛 0 | 📅 2021-03-29
* [UsbRt\_ROP](https://github.com/binarly-io/Research_Publications/tree/main/OffensiveCon_2022/UsbRt_ROP_PoC) ⭐ 134 | 🐛 0 | 🌐 Python | 📅 2026-03-09
* [Aptiocalypsis](https://github.com/Cr4sh/Aptiocalypsis) ⭐ 79 | 🐛 0 | 🌐 Python | 📅 2016-10-22
* [vulnerability-disclosures](https://github.com/eset/vulnerability-disclosures) ⭐ 28 | 🐛 0 | 📅 2022-07-13: Vulnerabilities found by ESET, some of the vulnerabilities in the repo related to UEFI.
* [vulnerabilities](https://github.com/10TG/vulnerabilities) ⭐ 8 | 🐛 0 | 📅 2023-05-15: Vulnerabilities found by 10TG, some of the vulnerabilities related to UEFI.
* [CERT/CC UEFI Analysis Resources](https://github.com/CERTCC/UEFI-Analysis-Resources) ⚠️ Archived: This repo contains an example of CVE-2021-28216
* [PixieFail: Nine vulnerabilities in Tianocore's EDK II IPv6 network stack.](https://blog.quarkslab.com/pixiefail-nine-vulnerabilities-in-tianocores-edk-ii-ipv6-network-stack.html)
* [CVE-2022-3430, CVE-2022-3431, CVE-2022-3432](https://twitter.com/ESETresearch/status/1590279786751881216): These three vulnerabilities are found by ESET Research, all of which are NVRAM vulnerabilities in Lenovo devices that could disable Secure Boot.
* [CVE-2022-4020](https://twitter.com/ESETresearch/status/1597227775420952579): NVRAM vulnerability found by ESET Research, which exists in Acer devices and could disable Secure Boot by setting a UEFI Variable.
* [CVE-2014-8274](https://www.kb.cert.org/vuls/id/976132)

## Talks :speaker:

| Year |      Conference      |                                                                                                                                                                   Title                                                                                                                                                                  |
| :--: | :------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 2024 |        Defcon        |                              [AMD Sinkclose: Universal Ring -2 Privilege Escalation](https://media.defcon.org/DEF%20CON%2032/DEF%20CON%2032%20presentations/DEF%20CON%2032%20-%20Enrique%20Nissim%20Krzysztof%20Okupski%20-%20AMD%20Sinkclose%20Universal%20Ring-2%20Privilege%20Escalation%20Redacted.pdf)                              |
| 2024 |     Blackhat USA     |                                                             [You've Already Been Hacked: What if There Is a Backdoor in Your UEFI OROM?](https://www.blackhat.com/us-24/briefings/schedule/#you39ve-already-been-hacked-what-if-there-is-a-backdoor-in-your-uefi-orom-39579)                                                             |
| 2024 | Blackhat USA ARSENAL | [Damn Vulnerable UEFI (DVUEFI): An Exploitation Toolkit and Learning Platform for Unveiling and Fixing UEFI Firmware Vulnerabilities](https://www.blackhat.com/us-24/arsenal/schedule/index.html#damn-vulnerable-uefi-dvuefi-an-exploitation-toolkit-and-learning-platform-for-unveiling-and-fixing-uefi-firmware-vulnerabilities-39058) |
| 2023 |    Blackhat Europe   |                                                                              [LogoFAIL: Security implications of image parsing during system boot](https://i.blackhat.com/EU-23/Presentations/EU-23-Pagani-LogoFAIL-Security-Implications-of-Image_REV2.pdf)                                                                             |
| 2023 |     Blackhat Asia    |                                                                        [The Various Shades of Supply Chain: SBOM, N-Days and Zero Trust](https://www.blackhat.com/asia-23/briefings/schedule/#the-various-shades-of-supply-chain-sbom-n-days-and-zero-trust-31253)                                                                       |
| 2021 |         AVAR         |                                                                           [The Evolution of Threat Actors: Firmware is the Next Frontier](https://github.com/binarly-io/Research_Publications/tree/main/AVAR_2021) ⭐ 134 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-09                                                                           |
| 2022 |     Blackhat USA     |                                                                [Breaking Firmware Trust From Pre-EFI: Exploiting Early Boot Phases](https://www.blackhat.com/us-22/briefings/schedule/index.html#breaking-firmware-trust-from-pre-efi-exploiting-early-boot-phases-27229)                                                                |
| 2022 |     Blackhat Asia    |                                                                           [The Firmware Supply-Chain Security Is Broken: Can We Fix It?](https://github.com/binarly-io/Research_Publications/tree/main/BHASIA_2022) ⭐ 134 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-09                                                                          |
| 2021 |     Blackhat USA     |                                                                                                             [Safeguarding UEFI Ecosystem: Firmware Supply Chain is Hard(coded)](https://www.youtube.com/watch?v=WMMdfnyiSd8)                                                                                                             |
| 2021 |     Blackhat USA     |                                                                                                                                [Breaking Secure Bootloaders](https://www.youtube.com/watch?v=XvGcQgx9Jg8)                                                                                                                                |
| 2020 |    Blackhat Europe   |                                                                                               [efiXplorer: Hunting for UEFI Firmware Vulnerabilities at Scale with Automated Static Analysis](https://www.youtube.com/watch?v=Sa779TGX3wY)                                                                                               |
| 2019 |     Blackhat USA     |                                                                                                           [Firmware Cartography: Charting the Course for Modern Server Compromise](https://www.youtube.com/watch?v=OwQ9MxGk8zs)                                                                                                          |
| 2019 |     Blackhat Asia    |                                                              [MODERN SECURE BOOT ATTACKS: Presenter’s Name Presenter's Position BYPASSING HARDWARE ROOT OF TRUST FROM SOFTWARE](https://i.blackhat.com/asia-19/Fri-March-29/bh-asia-Matrosov-Modern-Secure-Boot-Attacks.pdf)                                                             |
| 2019 |     Blackhat Asia    |                                          [Finally, I Can Sleep Tonight: Catching Sleep Mode Vulnerabilities of the TPM with Napper](https://i.blackhat.com/asia-19/Thu-March-28/bh-asia-Seunghun-Finally-I-Can-Sleep-Tonight-Catching-Sleep-Mode-Vulnerabilities-of-the-TPM-with-the-Napper.pdf)                                         |
| 2019 |     Blackhat USA     |                                                                                               [Breaking Through Another Side: Bypassing Firmware Security Boundaries from Embedded Controller](https://www.youtube.com/watch?v=g-1Y466rDaI)                                                                                              |
| 2018 |     Blackhat USA     |                                                                                                                          [Remotely Attacking System Firmware](https://www.youtube.com/watch?v=u1ErD7l0xXQ\&t=3s)                                                                                                                         |
| 2018 |    Blackhat Europe   |                                                                                                   [Malware Buried Deep Down the SPI Flash: Sednit's First UEFI Rootkit Found in the Wild](https://www.youtube.com/watch?v=sObGrnesxv4)                                                                                                   |
| 2018 |     Blackhat Asia    |                                                                        [I Don't Want to Sleep Subverting Intel TXT with S3 Sleep](https://i.blackhat.com/briefings/asia/2018/asia-18-Seunghun-I_Dont_Want_to_Sleep_Tonight_Subverting_Intel_TXT_with_S3_Sleep.pdf)                                                                       |
| 2017 |     Blackhat USA     |                                                                                                    [INTEL AMT. STEALTH BREAKTHROUGH](https://www.blackhat.com/docs/us-17/thursday/us-17-Evdokimov-Intel-AMT-Stealth-Breakthrough.pdf)                                                                                                    |
| 2017 |     Blackhat USA     |                                                                                                [Firmware is the New Black - Analyzing Past Three Years of BIOS/UEFI Security Vulnerabilities](https://www.youtube.com/watch?v=MONgHW2rpY8)                                                                                               |
| 2017 |     Blackhat USA     |                                                                                                              [Betraying the BIOS: Where the Guardians of the BIOS are Failing](https://www.youtube.com/watch?v=Dfl2JI2eLc8)                                                                                                              |
| 2017 |     Blackhat USA     |                                                                                                                            [Taking DMA Attacks to the Next Level](https://www.youtube.com/watch?v=QeIPcA8zsHk)                                                                                                                           |
| 2017 |     Blackhat Asia    |                                                                                                                       [The UEFI Firmware Rootkits: Myths and Reality](https://www.youtube.com/watch?v=P3yMXspLzoY)                                                                                                                       |
| 2017 |     Blackhat USA     |                                                                                                           [Fractured Backbone: Breaking Modern OS Defenses with Firmware Attacks](https://www.youtube.com/watch?v=ryKy9LvmSIs)                                                                                                           |
| 2014 |    Blackhat Europe   |                                                                                                              [Analyzing UEFI BIOSes from Attacker & Defender Viewpoints](https://www.youtube.com/watch?v=CGBpil0S5NI\&t=1s)                                                                                                              |
| 2014 |     Blackhat USA     |                                                                                                                   [Extreme Privilege Escalation on Windows 8/UEFI Systems](https://www.youtube.com/watch?v=X_Jxsl3vVcA)                                                                                                                  |
| 2014 |     Blackhat USA     |                                                                                                                 [Protecting Data In-Use from Firmware and Physical Attacks](https://www.youtube.com/watch?v=edNkIc6L9Qo)                                                                                                                 |
| 2014 |     Blackhat USA     |                                                                                                                           [Exposing Bootkits with BIOS Emulation](https://www.youtube.com/watch?v=siMj4bFx5nI)                                                                                                                           |
| 2013 |     Blackhat USA     |                                                                                                                   [A Tale of One Software Bypass of Windows 8 Secure Boot](https://www.youtube.com/watch?v=i9ULYwRK1iU)                                                                                                                  |
| 2013 |     Blackhat USA     |                                                                                                              [BIOS Chronamancy: Fixing the Core Root of Trust for Measurement](https://www.youtube.com/watch?v=eqdmJukaO6I)                                                                                                              |
| 2013 |     Blackhat USA     |                                                                                      [Funderbolt Adventures in Thunderbolt DMA Attacks](https://media.blackhat.com/us-13/US-13-Sevinsky-Funderbolt-Adventures-in-Thunderbolt-DMA-Attacks-Slides.pdf)                                                                                     |
| 2011 |       Blackhat       |                                                                                                         [Battery Firmware Hacking](https://media.blackhat.com/bh-us-11/Miller/BH_US_11_Miller_Battery_Firmware_Public_Slides.pdf)                                                                                                        |
| 2009 |     Blackhat USA     |                                                                                                        [Attacking Intel® BIOS](https://www.blackhat.com/presentations/bh-usa-09/WOJTCZUK/BHUSA09-Wojtczuk-AtkIntelBios-SLIDES.pdf)                                                                                                       |
| 2009 |     Blackhat USA     |                                                                                              [Reversing and Exploiting an Apple Firmware Update](https://www.blackhat.com/presentations/bh-usa-09/CHEN/BHUSA09-Chen-RevAppleFirm-SLIDES.pdf)                                                                                             |
| 2009 |      Blackhat DC     |                                                                                [Attacking Intel® Trusted Execution Technology](https://www.blackhat.com/presentations/bh-dc-09/Wojtczuk_Rutkowska/BlackHat-DC-09-Rutkowska-Attacking-Intel-TXT-slides.pdf)                                                                               |
| 2009 |       Blackhat       |                                                                                                                 [Introducing Ring -3 Rootkits](https://invisiblethingslab.com/resources/bh09usa/Ring%20-3%20Rootkits.pdf)                                                                                                                |
| 2008 |       Blackhat       |                                                                                                            [Preventing and Detecting Xen Hypervisor Subversions](https://invisiblethingslab.com/resources/bh08/part2-full.pdf)                                                                                                           |
| 2018 |      CanSecWest      |                                                             [TPM Genie Attacking the Hardware Root of Trust For Less Than $50](https://github.com/nccgroup/TPMGenie/blob/master/docs/CanSecWest_2018_-_TPM_Genie_-_Jeremy_Boone.pdf) ⭐ 228 \| 🐛 4 \| 🌐 C++ \| 📅 2021-01-04                                                            |
| 2015 |      CanSecWest      |                                                                                                                                            [A New Class of Vulnerabilities in SMI Handlers]()                                                                                                                                            |
| 2015 |      CanSecWest      |                                                                                                    [Attacks on UEFI Security](https://web.archive.org/web/20150908083304/https://cansecwest.com/slides/2015/AttacksOnUEFI_Rafal.pptx)                                                                                                    |
| 2014 |      CanSecWest      |                                                                                                              [ALL YOUR BOOT ARE BELONG TO US](https://papers.put.as/papers/firmware/2014/AllYourBoot_csw14-mitre-final.pdf)                                                                                                              |
| 2009 |      CanSecWest      |                                                                                                     [Getting into the SMRAM: SMM Reloaded](https://web.archive.org/web/20090419080356/https://cansecwest.com/csw09/csw09-duflot.pdf)                                                                                                     |
| 2022 |        DEFCON        |                                                                                                                     [The COW Container On Windows Who Escaped the Silo](https://www.youtube.com/watch?v=Xte4IKnRqao)                                                                                                                     |
| 2022 |        DEFCON        |                                                                                                                              [One Bootloader to Load Them All](https://www.youtube.com/watch?v=99t7wEYs8h0)                                                                                                                              |
| 2021 |        DEFCON        |                                                                                                                         [High Stakes Updates: BIOS RCE OMG WTF BBQ](https://www.youtube.com/watch?v=qxWfkSonK7M)                                                                                                                         |
| 2019 |        DEFCON        |                                                                                                                              [UEFI Exploitation for the Masses](https://www.youtube.com/watch?v=CxqNgjMZAbk)                                                                                                                             |
| 2019 |        DEFCON        |                                                                                                                         [Ring 0 Ring 2 Rootkits Bypassing Defenses](https://www.youtube.com/watch?v=7AEMxaZhdLU)                                                                                                                         |
| 2019 |        DEFCON        |                                                                                                                                [ EDR is Coming Hide Yo Sh!t ](https://www.youtube.com/watch?v=q2KUufrjoRo)                                                                                                                               |
| 2017 |        DEFCON        |                                                                                             [Safeguarding rootkits: IntelBootGuard](https://github.com/flothrone/bootguard/blob/master/Intel%20BG%20part2.pdf) ⭐ 120 \| 🐛 0 \| 📅 2020-12-03                                                                                            |
| 2018 |        DEFCON        |                                                                                                                               [Disabling Intel ME in Firmware](https://www.youtube.com/watch?v=WJo8RsJeqxU)                                                                                                                              |
| 2014 |        DEFCON        |                                                                                                                   [Extreme Privilege Escalation On Windows 8/UEFI Systems](https://www.youtube.com/watch?v=d6VCri6sPnY)                                                                                                                  |
| 2013 |        DEFCON        |                                                                                                                               [Hacking Measured Boot and UEFI](https://www.youtube.com/watch?v=9owW2q6SJew)                                                                                                                              |
| 2020 |        DEFCON        |                                                                                                                                [OuterHaven UEFI Memory Space](https://www.youtube.com/watch?v=cTKrVGVFp5k)                                                                                                                               |
| 2008 |        DEFCON        |                                            [Bypassing pre-boot authentication passwords by instrumenting the BIOS keyboard buffer(pratical low level attacks against x86 authentication software)](https://defcon.org/images/defcon-16/dc16-presentations/brossard/defcon-16-brossard-wp.pdf)                                            |
| 2007 |        DEFCON        |                                                                                                                         [ Hacking the Extensible Firmware Interface](https://www.youtube.com/watch?v=g-n42Q-Pxsg)                                                                                                                        |
| 2022 |         H2HC         |                                                                                        [Data-only Attacks Against UEFI BIOS](https://github.com/binarly-io/Research_Publications/tree/main/H2HC_2022) ⭐ 134 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-09                                                                                        |
| 2022 |     Offensive Con    |                                                                          [UEFI Firmware Vulnerabilities: Past, Present and Future](https://github.com/binarly-io/Research_Publications/tree/main/OffensiveCon_2022) ⭐ 134 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-09                                                                          |
| 2017 |         REcon        |                                                                                              [BARing the System New vulnerabilities in Coreboot & UEFI based systems](http://www.c7zero.info/stuff/REConBrussels2017_BARing_the_system.pdf)                                                                                              |

## Blogs :newspaper:

* [Binarly-IO](https://www.binarly.io)
  * [Multiple Vulnerabilities In Qualcomm And Lenovo ARM-Based Devices](https://www.binarly.io/posts/Multiple_Vulnerabilities_in_Qualcomm_and_Lenovo_ARM_based_Devices)
  * [Firmware Patch Deep-Dive: Lenovo Patches Fail To Fix Underlying Vulnerabilities]()
  * [OpenSSL Usage In UEFI Firmware Exposes Weakness In SBOMs](https://www.binarly.io/posts/OpenSSL_Usage_in_UEFI_Firmware_Exposes_Weakness_in_SBOMs/index.html)
  * [The Firmware Supply-Chain Security Is Broken: Can We Fix It?](https://binarly.io/posts/The_Firmware_Supply_Chain_Security_is_broken_Can_we_fix_it/index.html)
  * [Leaked Intel Boot Guard Keys: What Happened? How Does It Affect The Software Supply Chain?](https://www.binarly.io/posts/Leaked_Intel_Boot_Guard_keys_What_happened_How_does_it_affect_the_software_supply_chain/index.html)
  * [New Attacks To Disable And Bypass Windows Management Instrumentation ](https://www.binarly.io/posts/New_Attacks_to_Disable_and_Bypass_Windows_Management_Instrumentation_LABSCon_Edition/index.html)
  * [Binarly Discloses High-Impact Firmware Vulnerabilities In Insyde-Based Devices](https://www.binarly.io/posts/LABScon_2022_Binarly_Discloses_High_Impact_Firmware_Vulnerabilities_In_Insyde_Based_Devices/index.html)
  * [Binarly Discovers Multiple High-Severity Vulnerabilities In AMI-Based Devices](https://www.binarly.io/posts/Binarly_Discovers_Multiple_High_Severity_Vulnerabilities_in_AMI_based_Devices/index.html)
  * [Binarly Finds Six High Severity Firmware Vulnerabilities In HP Enterprise Devices](https://www.binarly.io/posts/Binarly_Finds_Six_High_Severity_Firmware_Vulnerabilities_in_HP_Enterprise_Devices/index.html)
  * [The Intel PPAM Attack Story](https://binarly.io/posts/Black_Hat_2022_The_Intel_PPAM_attack_story/index.html)
  * [Using Symbolic Execution To Detect UEFI Firmware Vulnerabilities](https://www.binarly.io/posts/Using_Symbolic_Execution_to_Detect_UEFI_Firmware_Vulnerabilities/index.html)
  * [Blasting Event-Driven Cornucopia](https://www.binarly.io/posts/Black_Hat_2022_Blasting_Event_Driven_Cornucopia_WMI_edition/index.html)
  * [FirmwareBleed: The Industry Fails To Adopt Return Stack Buffer Mitigations In SMM](https://www.binarly.io/posts/FirmwareBleed_The_industry_fails_to_adopt_Return_Stack_Buffer_mitigations_in_SMM/index.html)
  * [FwHunt The Next Chapter: Firmware Threat Detection At Scale](https://binarly.io/posts/FwHunt_The_Next_Chapter_Firmware_Threat_Detection_at_Scale/index.html)
  * [A Deeper UEFI Dive Into MoonBounce](https://www.binarly.io/posts/A_deeper_UEFI_dive_into_MoonBounce/index.html)
  * [Repeatable Failures: AMI UsbRt - Six Years Later, Firmware Attack Vector Still Affect Millions Of Enterprise Devices](https://www.binarly.io/posts/AMI_UsbRt_Repeatable_Failures_A_6_year_old_attack_vector_still_affecting_millions_of_enterprise_devices/index.html)
  * [Repeatable Firmware Security Failures: 16 High Impact Vulnerabilities Discovered In HP Devices](https://www.binarly.io/posts/Repeatable_Firmware_Security_Failures_16_High_Impact_Vulnerabilities_Discovered_in_HP_Devices/index.html)
  * [An In-Depth Look At The 23 High-Impact Vulnerabilities](https://www.binarly.io/posts/An_In_Depth_Look_at_the_23_High_Impact_Vulnerabilities/index.html)
  * [Detecting Firmware Vulnerabilities At Scale: Intel BSSA DFT Case Study](https://www.binarly.io/posts/Detecting_Firmware_vulnerabilities_at_scale_Intel_BSSA_DFT_case_study)
  * [Why Firmware Integrity Is Insufficient For Effective Threat Detection And Hunting](https://www.binarly.io/posts/Why_Firmware_Integrity_is_Insufficient_for_Effective_Threat_Detection_and_Hunting/index.html)
  * [Firmware Supply Chain Is Hard(Coded)](https://www.binarly.io/posts/Firmware_Supply_Chain_is_Hard\(coded\)/index.html)
  * [Attacking (Pre)EFI Ecosystem](https://www.binarly.io/posts/Attacking_\(pre\)EFI_Ecosystem/index.html)

* [Cr4sh](http://blog.cr4.sh/)
  * [Exploiting AMI Aptio firmware on example of Intel NUC](http://blog.cr4.sh/2016/10/exploiting-ami-aptio-firmware.html)
  * [Exploring and exploiting Lenovo firmware secrets](http://blog.cr4.sh/2016/06/exploring-and-exploiting-lenovo.html)
  * [Exploiting SMM callout vulnerabilities in Lenovo firmware](http://blog.cr4.sh/2016/02/exploiting-smm-callout-vulnerabilities.html)
  * [Breaking UEFI security with software DMA attacks](http://blog.cr4.sh/2015/09/breaking-uefi-security-with-software.html)
  * [Building reliable SMM backdoor for UEFI based platforms](http://blog.cr4.sh/2015/07/building-reliable-smm-backdoor-for-uefi.html)
  * [Exploiting UEFI boot script table vulnerability](http://blog.cr4.sh/2015/02/exploiting-uefi-boot-script-table.html)

* [eclypsium](https://eclypsium.com)
  * [FIRMWARE ATTACKS: AN ENDPOINT TIMELINE](https://eclypsium.com/2022/10/20/firmware-attacks-an-endpoint-timeline/)
  * [ONE BOOTLOADER TO LOAD THEM ALL](https://eclypsium.com/2022/08/11/vulnerable-bootloaders-2022/)
  * [FIRMWARE SECURITY REALIZATIONS – PART 2 – START YOUR MANAGEMENT ENGINE](https://eclypsium.com/2022/08/10/firmware-security-realizations-part-2-start-your-management-engine/)
  * [FIRMWARE SECURITY REALIZATIONS – PART 1 – SECURE BOOT AND DBX](https://eclypsium.com/2022/07/26/firmware-security-realizations-part-1-secure-boot-and-dbx/)
  * [YET ANOTHER UEFI BOOTKIT DISCOVERED: MEET COSMICSTRAND](https://eclypsium.com/2022/07/28/yet-another-uefi-bootkit-discovered-meet-cosmicstrand/)
  * [THE ILOBLEED IMPLANT: LIGHTS OUT MANAGEMENT LIKE YOU WOULDN’T BELIEVE](https://eclypsium.com/2022/01/12/the-ilobleed-implant-lights-out-management-like-you-wouldnt-believe/)
  * [“EVIL MAID” FIRMWARE ATTACKS USING USB DEBUG](https://eclypsium.com/2018/07/23/evil-maid-firmware-attacks-using-usb-debug/)

* [ESET Research](https://www.welivesecurity.com)
  * [BlackLotus UEFI bootkit: Myth confirmed
    ](https://www.welivesecurity.com/2023/03/01/blacklotus-uefi-bootkit-myth-confirmed/)
  * [ESET Research Podcast: UEFI in crosshairs of ESPecter bootkit
    ](https://www.welivesecurity.com/2022/05/26/eset-research-podcast-uefi-crosshairs-especter-bootkit/)
  * [When “secure” isn’t secure at all: High‑impact UEFI vulnerabilities discovered in Lenovo consumer laptops](https://www.welivesecurity.com/2022/04/19/when-secure-isnt-secure-uefi-vulnerabilities-lenovo-consumer-laptops/)
  * [UEFI threats moving to the ESP: Introducing ESPecter bootkit](https://www.welivesecurity.com/2021/10/05/uefi-threats-moving-esp-introducing-especter-bootkit/)
  * [Needles in a haystack: Picking unwanted UEFI components out of millions of samples](https://www.welivesecurity.com/2019/10/08/needles-haystack-unwanted-uefi-components/)
  * [A machine‑learning method to explore the UEFI landscape](https://www.welivesecurity.com/wp-content/uploads/2019/10/ESET_Machine_Learning_UEFI.pdf)
  * [LOJAX: First UEFI rootkit found in the wild, courtesy of the Sednit group](https://www.welivesecurity.com/2018/09/27/lojax-first-uefi-rootkit-found-wild-courtesy-sednit-group/)
  * [UEFI malware: How to exploit a false sense of security](https://www.welivesecurity.com/2017/10/19/malware-firmware-exploit-sense-security/)
  * [Bootkit Threat Evolution in 2011](https://www.welivesecurity.com/2012/01/03/bootkit-threat-evolution-in-2011-2/)

* [Sentinel Lab](https://sentinelone.com/)
  * [Moving From Common-Sense Knowledge About UEFI To Actually Dumping UEFI Firmware](https://www.sentinelone.com/labs/moving-from-common-sense-knowledge-about-uefi-to-actually-dumping-uefi-firmware/)
  * [Moving From Manual Reverse Engineering of UEFI Modules To Dynamic Emulation of UEFI Firmware](https://www.sentinelone.com/labs/moving-from-manual-reverse-engineering-of-uefi-modules-to-dynamic-emulation-of-uefi-firmware/)
  * [Moving From Dynamic Emulation of UEFI Modules To Coverage-Guided Fuzzing of UEFI Firmware](https://www.sentinelone.com/labs/moving-from-dynamic-emulation-of-uefi-modules-to-coverage-guided-fuzzing-of-uefi-firmware/)
  * [Adventures From UEFI Land: the Hunt For the S3 Boot Script](https://www.sentinelone.com/labs/adventures-from-uefi-land-the-hunt-for-the-s3-boot-script/)
  * [Zen and the Art of SMM Bug Hunting | Finding, Mitigating and Detecting UEFI Vulnerabilities](https://www.sentinelone.com/labs/zen-and-the-art-of-smm-bug-hunting-finding-mitigating-and-detecting-uefi-vulnerabilities/)
  * [Another Brick in the Wall: Uncovering SMM Vulnerabilities in HP Firmware](https://www.sentinelone.com/labs/another-brick-in-the-wall-uncovering-smm-vulnerabilities-in-hp-firmware/)

* [SYNACKTIV](https://www.synacktiv.com)
  * [Code Check(Mate) in SMM](https://www.synacktiv.com/en/publications/code-checkmate-in-smm.html)
  * [Through The SMM-Glass And a Vulnerability Found There.](https://www.synacktiv.com/publications/through-the-smm-class-and-a-vulnerability-found-there.html)
  * [A Journey in Reversing UEFI Lenovo Passwords Management](https://www.synacktiv.com/publications/a-journey-in-reversing-uefi-lenovo-passwords-management.html)
  * [S3 Sleep, Resume and Handling Them with Type-1 Hypervisor](https://standa-note.blogspot.com/2020/11/s3-sleep-resume-and-handling-them-with.html)
  * [Introductory Study of IOMMU (VT-d) and Kernel DMA Protection on Intel Processors](https://standa-note.blogspot.com/2020/05/introductory-study-of-iommu-vt-d-and.html)

* [NCCGroup](https://research.nccgroup.com)
  * [Stepping Insyde System Management Mode](https://research.nccgroup.com/2023/04/11/stepping-insyde-system-management-mode/)
  * [A Race to Report a TOCTOU: Analysis of a Bug Collision in Intel SMM](https://research.nccgroup.com/2023/03/15/a-race-to-report-a-toctou-analysis-of-a-bug-collision-in-intel-smm/)
  * [Intel BIOS Advisory – Memory Corruption in HID Drivers ](https://research.nccgroup.com/2023/08/08/intel-bios-advisory-memory-corruption-in-hid-drivers/)

* Others
  * [Debugging System with DCI and Windbg](https://standa-note.blogspot.com/2021/03/debugging-system-with-dci-and-windbg.html)
  * [Reverse engineering (Absolute) UEFI modules for beginners](https://standa-note.blogspot.com/2021/04/reverse-engineering-absolute-uefi.html)
  * [Experiment in extracting runtime drivers on Windows](https://standa-note.blogspot.com/2020/12/experiment-in-extracting-runtime.html)
  * [BIOS Based Rootkits](http://www.exfiltrated.com/research-BIOS_Based_Rootkits.php)
  * [Understanding modern UEFI-based platform boot](https://depletionmode.com/uefi-boot.html)
  * [Attacking UEFI Runtime Services and Linux](http://blog.frizk.net/2017/01/attacking-uefi-and-linux.html)
  * [Using an Unimpressive Bug in EDK II to Do Some Fun Exploitation](https://blog.quarkslab.com/for-science-using-an-unimpressive-bug-in-edk-ii-to-do-some-fun-exploitation.html)

## Papers :page\_with\_curl:

| Year |    Jour/Conf   |                                                                                                          Paper                                                                                                          |
| :--: | :------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| 2025 |      arXiv     |                                                             [UEFI Memory Forensics: A Framework for UEFI Threat Analysis](https://arxiv.org/pdf/2501.16962)                                                             |
| 2025 |      NDSS      |                                                          [FUZZUER: Enabling Fuzzing of UEFI Interfaces on EDK-2](https://machiry.github.io/files/fuzzuerr.pdf)                                                          |
| 2024 |       ASE      |                                      [STASE: Static Analysis Guided Symbolic Execution for UEFI Vulnerability Signature Generation](https://dl.acm.org/doi/10.1145/3691620.3695543)                                     |
| 2023 |      S\&P      |                     [RSFUZZER: Discovering Deep SMI Handler Vulnerabilities in UEFI Firmware with Hybrid Fuzzing](https://www.computer.org/csdl/proceedings-article/sp/2023/933600b765/1Js0Ek1SE6c)                     |
| 2023 |      arXiv     |                                                               [SoK: Security Below the OS – A Security Analysis of UEFI](http://arxiv.org/abs/2311.03809)                                                               |
| 2023 |    China CIC   |                                        [A Survey on the Evolution of Bootkits Attack and Defense Techniques](http://www.cic-chinacommunications.cn/EN/10.23919/JCC.ja.2022-0409)                                        |
| 2022 |      S\&P      |                                 [Finding SMM Privilege-Escalation Vulnerabilities in UEFI Firmware with Protocol-Centric Static Analysis](https://dblp.uni-trier.de/conf/sp/YinLWSZHX22)                                |
| 2022 |    IH\&MMSec   | [Hidden in Plain Sight - Persistent Alternative Mass Storage Data Streams as a Means for Data Hiding With the Help of UEFI NVRAM and Implications for IT Forensics](https://dl.acm.org/doi/pdf/10.1145/3531536.3532965) |
| 2020 |       DAC      |                                                           [UEFI Firmware Fuzzing with Simics Virtual Platform](https://dblp.uni-trier.de/conf/dac/YangVYYZ20)                                                           |
| 2015 |     SYSTOR     |                                                       [Thunderstrike:EFI firmware bootkits for Apple MacBooks](https://dl.acm.org/doi/pdf/10.1145/2757667.2757673)                                                      |
| 2015 |      WOOT      |                                                 [Symbolic execution for BIOS security](https://www.usenix.org/system/files/conference/woot15/woot15-paper-bazhaniuk.pdf)                                                |
| 2014 | Virus Bulletin |                                               [Bootkits: Past, Present & Future](https://www.virusbulletin.com/uploads/pdf/conference/vb2014/VB2014-RodionovMatrosov.pdf)                                               |
| 2011 |                |                                   [Attacking Intel TXT® via SINIT code execution hijacking](https://invisiblethingslab.com/resources/2011/Attacking_Intel_TXT_via_SINIT_hijacking.pdf)                                  |
| 2014 |                |                  [Speed Racer: Exploiting an Intel Flash Protection Race Condition](https://fahrplan.events.ccc.de/congress/2014/Fahrplan/system/attachments/2565/original/speed_racer_whitepaper.pdf)                  |

## Training & Courses :beginner:

* [Advanced x86: Introduction to BIOS & SMM](https://opensecuritytraining.info/IntroBIOS.html)
* [UEFI Official Learning Center](https://uefi.org/learning_center)
* [EDK II Secure Code Review Guide](https://edk2-docs.gitbook.io/edk-ii-secure-code-review-guide/)
* [Tianocore Training Contents](https://github.com/tianocore-training/Tianocore_Training_Contents/wiki) ⭐ 89 | 🐛 3 | 🌐 CSS | 📅 2021-09-16

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
