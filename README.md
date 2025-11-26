# AvatarX

**AvatarX is an enhanced, reorganized version of the Microsoft Rocketbox
Avatar Library --- optimized, modernized, and ready for game engines,
simulation, VR, and AI-driven characters.**

AvatarX builds on the original **115 fully-rigged Rocketbox avatars**, a
collection developed over more than 10 years and widely used by research
laboratories worldwide. Thanks to their consistent rigs, relatively
low-poly meshes, and broad diversity, Rocketbox avatars became a
standard for:

-   Crowd simulation\
-   Real-time embodied avatars\
-   Social VR\
-   Behavioral research\
-   AI agent embodiment\
-   Digital twin systems\
-   Academic virtual reality studies

AvatarX preserves this important foundation while providing a **clean
structure, updated metadata, engine-ready organization**, and optional
tools to make the avatars easier to use in modern production pipelines.

------------------------------------------------------------------------

## 🔍 Research Background

The Rocketbox library has been cited extensively in VR, simulation, and
cognitive science research.

If you use AvatarX in academic work, please cite the original Rocketbox
paper:

**The Rocketbox library and the utility of freely available rigged
avatars**\
Mar Gonzalez-Franco, Eyal Ofek, Ye Pan, Angus Antley, Anthony Steed,
Bernhard Spanlang, Antonella Maselli, Domna Banakou, Nuria Pelechano,
Sergio Orts Escolano, Veronica Orvalho, Laura Trutoiu, Markus Wojcik,
Maria V. Sanchez-Vives, Jeremy Bailenson, and Jaron Lanier\
Frontiers in Virtual Reality (2020)\
DOI:
https://www.frontiersin.org/articles/10.3389/frvir.2020.561558/abstract

Original Microsoft announcement:\
https://www.microsoft.com/en-us/research/blog/microsoft-rocketbox-avatar-library-now-available-for-research-and-academic-use/

------------------------------------------------------------------------

## ✨ Improvements in AvatarX

AvatarX reorganizes and enhances the original library:

-   Clean, modern folder structure\
-   Consistent file naming\
-   Unity-ready and engine-agnostic project layout\
-   Updated rig notes, expressions, blendshape documentation\
-   Optional import helpers for Unity\
-   Improved discoverability and workflow organization\
-   Clear separation between MIT-licensed Rocketbox assets and AvatarX
    additions

These updates make the library dramatically easier to integrate into
modern engines and pipelines.

------------------------------------------------------------------------

## 🔗 Compatibility & Ecosystem

AvatarX is **100% compatible with PhonemeX Pro -- Unlimited
Cross-Platform TTS with Phoneme Access**\
Unity Asset Store:
https://assetstore.unity.com/packages/tools/generative-ai/phonemex-pro-edition-unlimited-cross-platform-tts-with-phoneme-a-316336

Because the avatars use consistent humanoid rigs and standardized
blendshape naming, they integrate seamlessly with PhonemeX Pro's
advanced phoneme-driven facial animation system. You can:

-   Generate natural lip-sync directly from TTS audio\
-   Use phoneme-accurate viseme blending\
-   Combine visemes with Rocketbox/AvatarX facial blendshapes\
-   Create expressive speaking characters for NPCs, VR, training, and AI
    agents

**AvatarX + PhonemeX Pro** provides a complete pipeline for lightweight,
expressive, real-time digital characters.

------------------------------------------------------------------------

## 📚 Rocketbox Update History (Preserved)

AvatarX includes and preserves the improvements added to Rocketbox over
time:

-   **2022:** ARKit-compatible blendshapes\
-   **2022:** 417 compatible animations\
-   **2022:** Headbox facial blendshape transfer library\
-   **2022:** Facial blendshapes (15 visemes, 48 FACS, 30 Vive Tracker
    shapes)\
-   **2021:** Unreal batch importer\
-   **2020:** MoveBox animation library\
-   **2020:** MIT license update

All included assets remain under the MIT License.

------------------------------------------------------------------------

## 🚀 Getting Started (Unity Workflow)

1.  Import the desired AvatarX model folder (FBX + textures) into your
    Unity `Assets` directory.\
2.  (Optional) Use provided import helpers to:
    -   Correct 3dsMax material assumptions\
    -   Fix transparency & specular issues\
    -   Organize rigs into T-pose\
    -   Select preferred poly density\
3.  Drag the avatar prefab into your scene.\
4.  (Optional) Add PhonemeX Pro for phoneme-driven lip-sync and
    expressive facial animation.

------------------------------------------------------------------------

## 📂 Repository Structure

    AvatarX/
     ├── AvatarX_Models/               # MIT-licensed Rocketbox avatars
     ├── AvatarX_Metadata/             # Rig notes, expressions, blendshape docs
     ├── AvatarX_Unity/                # Unity helpers and sample setups
     ├── AvatarX_Samples/              # Example scenes
     ├── LICENSE_Rocketbox.txt         # Original MIT license
     └── THIRD_PARTY_NOTICES.md        # Attribution + citations

------------------------------------------------------------------------

## 🙏 Original Rocketbox Contributors

Mar Gonzalez-Franco\
Markus Wojcik\
Eyal Ofek\
Anthony Steed\
Dave Garagan\
Matias Volonte\
Fang Ma\
And many other contributors acknowledged in the original library.

Their work made this avatar library possible.

------------------------------------------------------------------------

## 📜 License

AvatarX includes assets originally from **Microsoft Rocketbox**,
licensed under the **MIT License**.\
All original license files and attribution are preserved.

All AvatarX additions in this repository are also MIT-licensed.

------------------------------------------------------------------------

## 🤝 Contributing

Contributions to improve structure, metadata, tooling, or integrations
are welcome.
