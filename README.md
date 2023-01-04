# pawn-tailwind

[![sampctl](https://img.shields.io/badge/sampctl-pawn--tailwind-2f2f2f.svg?style=for-the-badge)](https://github.com/Mysy00/pawn-tailwind)

<!--
Short description of your library, why it's useful, some examples, pictures or
videos. Link to your forum release thread too.

Remember: You can use "forumfmt" to convert this readme to forum BBCode!

What the sections below should be used for:

`## Installation`: Leave this section un-edited unless you have some specific
additional installation procedure.

`## Testing`: Whether your library is tested with a simple `main()` and `print`,
unit-tested, or demonstrated via prompting the player to connect, you should
include some basic information for users to try out your code in some way.

And finally, maintaining your version number`:

* Follow [Semantic Versioning](https://semver.org/)
* When you release a new version, update `VERSION` and `git tag` it
* Versioning is important for sampctl to use the version control features

Happy Pawning!
-->

## Installation

Simply install to your project:

```bash
sampctl package install Mysy00/pawn-tailwind
```

Include in your code and begin using the library:

```pawn
#include <tailwind-colors>
```

## Usage

<!--
Write your code documentation or examples here. If your library is documented in
the source code, direct users there. If not, list your API and describe it well
in this section. If your library is passive and has no API, simply omit this
section.
-->
Use one of the defines.

```pawn
#define C_GREY_0                    0xFAFAFAFF
#define C_GREY_1                    0xF5F5F5FF
#define C_GREY_2                    0xE5E5E5FF
#define C_GREY_3                    0xD4D4D4FF
#define C_GREY_4                    0xA3A3A3FF
#define C_GREY_5                    0x737373FF
#define C_GREY_6                    0x525252FF
#define C_GREY_7                    0x404040FF
#define C_GREY_8                    0x262626FF
#define C_GREY_9                    0x171717FF

#define C_RED_0                     0xfef2f2FF
#define C_RED_1                     0xfee2e2FF
#define C_RED_2                     0xfecacaFF
#define C_RED_3                     0xfca5a5FF
#define C_RED_4                     0xf87171FF
#define C_RED_5                     0xef4444FF
#define C_RED_6                     0xdc2626FF
#define C_RED_7                     0xb91c1cFF
#define C_RED_8                     0x991b1bFF
#define C_RED_9                     0x7f1d1dFF

#define C_ORANGE_0                  0xfff7edFF
#define C_ORANGE_1                  0xffedd5FF
#define C_ORANGE_2                  0xfed7aaFF
#define C_ORANGE_3                  0xfdba74FF
#define C_ORANGE_4                  0xfb923cFF
#define C_ORANGE_5                  0xf97316FF
#define C_ORANGE_6                  0xea580cFF
#define C_ORANGE_7                  0xc2410cFF
#define C_ORANGE_8                  0x9a3412FF
#define C_ORANGE_9                  0x7c2d12FF

#define C_AMBER_0                   0xfffbebFF
#define C_AMBER_1                   0xfef3c7FF
#define C_AMBER_2                   0xfde68aFF
#define C_AMBER_3                   0xfcd34dFF
#define C_AMBER_4                   0xfbbf24FF
#define C_AMBER_5                   0xf59e0bFF
#define C_AMBER_6                   0xd97706FF
#define C_AMBER_7                   0xb45309FF
#define C_AMBER_8                   0x92400eFF
#define C_AMBER_9                   0x78350fFF

#define C_YELLOW_0                  0xFEFCE8FF
#define C_YELLOW_1                  0xFEF9C3FF
#define C_YELLOW_2                  0xFEF08AFF
#define C_YELLOW_3                  0xFDE047FF
#define C_YELLOW_4                  0xFACC15FF
#define C_YELLOW_5                  0xEAB308FF
#define C_YELLOW_6                  0xCA8A04FF
#define C_YELLOW_7                  0xA16207FF
#define C_YELLOW_8                  0x854D0EFF
#define C_YELLOW_9                  0x713F12FF

#define C_LIME_0                    0xf7fee7FF
#define C_LIME_1                    0xecfccbFF
#define C_LIME_2                    0xd9f99dFF
#define C_LIME_3                    0xbef264FF
#define C_LIME_4                    0xa3e635FF
#define C_LIME_5                    0x84cc16FF
#define C_LIME_6                    0x65a30dFF
#define C_LIME_7                    0x4d7c0fFF
#define C_LIME_8                    0x3f6212FF
#define C_LIME_9                    0x365314FF

#define C_GREEN_0                   0xf0fdf4FF
#define C_GREEN_1                   0xdcfce7FF
#define C_GREEN_2                   0xbbf7d0FF
#define C_GREEN_3                   0x86efacFF
#define C_GREEN_4                   0x4ade80FF
#define C_GREEN_5                   0x22c55eFF
#define C_GREEN_6                   0x16a34aFF
#define C_GREEN_7                   0x15803dFF
#define C_GREEN_8                   0x166534FF
#define C_GREEN_9                   0x14532dFF

#define C_EMERALD_0                 0xecfdf5FF
#define C_EMERALD_1                 0xd1fae5FF
#define C_EMERALD_2                 0xa7f3d0FF
#define C_EMERALD_3                 0x6ee7b7FF
#define C_EMERALD_4                 0x34d399FF
#define C_EMERALD_5                 0x10b981FF
#define C_EMERALD_6                 0x059669FF
#define C_EMERALD_7                 0x047857FF
#define C_EMERALD_8                 0x065f46FF
#define C_EMERALD_9                 0x064e3bFF

#define C_TEAL_0                    0xf0fdfaFF
#define C_TEAL_1                    0xccfbf1FF
#define C_TEAL_2                    0x99f6e4FF
#define C_TEAL_3                    0x5eead4FF
#define C_TEAL_4                    0x2dd4bfFF
#define C_TEAL_5                    0x14b8a6FF
#define C_TEAL_6                    0x0d9488FF
#define C_TEAL_7                    0x0f766eFF
#define C_TEAL_8                    0x115e59FF
#define C_TEAL_9                    0x134e4aFF

#define C_CYAN_0                    0xecfeffFF
#define C_CYAN_1                    0xcffafeFF
#define C_CYAN_2                    0xa5f3fcFF
#define C_CYAN_3                    0x67e8f9FF
#define C_CYAN_4                    0x22d3eeFF
#define C_CYAN_5                    0x06b6d4FF
#define C_CYAN_6                    0x0891b2FF
#define C_CYAN_7                    0x0e7490FF
#define C_CYAN_8                    0x155e75FF
#define C_CYAN_9                    0x164e63FF

#define C_SKY_0                     0xf0f9ffFF
#define C_SKY_1                     0xe0f2feFF
#define C_SKY_2                     0xbae6fdFF
#define C_SKY_3                     0x7dd3fcFF
#define C_SKY_4                     0x38bdf8FF
#define C_SKY_5                     0x0ea5e9FF
#define C_SKY_6                     0x0284c7FF
#define C_SKY_7                     0x0369a1FF
#define C_SKY_8                     0x075985FF
#define C_SKY_9                     0x0c4a6eFF

#define C_BLUE_0                    0xeff6ffFF
#define C_BLUE_1                    0xdbeafeFF
#define C_BLUE_2                    0xbfdbfeFF
#define C_BLUE_3                    0x93c5fdFF
#define C_BLUE_4                    0x60a5faFF
#define C_BLUE_5                    0x3b82f6FF
#define C_BLUE_6                    0x2563ebFF
#define C_BLUE_7                    0x1d4ed8FF
#define C_BLUE_8                    0x1e40afFF
#define C_BLUE_9                    0x1e3a8aFF

#define C_INDIGO_0                  0xeef2ffFF
#define C_INDIGO_1                  0xe0e7ffFF
#define C_INDIGO_2                  0xc7d2feFF
#define C_INDIGO_3                  0xa5b4fcFF
#define C_INDIGO_4                  0x818cf8FF
#define C_INDIGO_5                  0x6366f1FF
#define C_INDIGO_6                  0x4f46e5FF
#define C_INDIGO_7                  0x4338caFF
#define C_INDIGO_8                  0x3730a3FF
#define C_INDIGO_9                  0x312e81FF

#define C_VIOLET_0                  0xf5f3ffFF
#define C_VIOLET_1                  0xede9feFF
#define C_VIOLET_2                  0xddd6feFF
#define C_VIOLET_3                  0xc4b5fdFF
#define C_VIOLET_4                  0xa78bfaFF
#define C_VIOLET_5                  0x8b5cf6FF
#define C_VIOLET_6                  0x7c3aedFF
#define C_VIOLET_7                  0x6d28d9FF
#define C_VIOLET_8                  0x5b21b6FF
#define C_VIOLET_9                  0x4c1d95FF

#define C_PURPLE_0                  0xfaf5ffFF
#define C_PURPLE_1                  0xf3e8ffFF
#define C_PURPLE_2                  0xe9d5ffFF
#define C_PURPLE_3                  0xd8b4feFF
#define C_PURPLE_4                  0xc084fcFF
#define C_PURPLE_5                  0xa855f7FF
#define C_PURPLE_6                  0x9333eaFF
#define C_PURPLE_7                  0x7e22ceFF
#define C_PURPLE_8                  0x6b21a8FF
#define C_PURPLE_9                  0x581c87FF

#define C_FUCHSIA_0                 0xfdf4ffFF
#define C_FUCHSIA_1                 0xfae8ffFF
#define C_FUCHSIA_2                 0xf5d0feFF
#define C_FUCHSIA_3                 0xf0abfcFF
#define C_FUCHSIA_4                 0xe879f9FF
#define C_FUCHSIA_5                 0xd946efFF
#define C_FUCHSIA_6                 0xc026d3FF
#define C_FUCHSIA_7                 0xa21cafFF
#define C_FUCHSIA_8                 0x86198fFF
#define C_FUCHSIA_9                 0x701a75FF

#define C_PINK_0                    0xfdf2f8FF
#define C_PINK_1                    0xfce7f3FF
#define C_PINK_2                    0xfbcfe8FF
#define C_PINK_3                    0xf9a8d4FF
#define C_PINK_4                    0xf472b6FF
#define C_PINK_5                    0xec4899FF
#define C_PINK_6                    0xdb2777FF
#define C_PINK_7                    0xbe185dFF
#define C_PINK_8                    0x9d174dFF
#define C_PINK_9                    0x831843FF

#define C_ROSE_0                    0xfff1f2FF
#define C_ROSE_1                    0xffe4e6FF
#define C_ROSE_2                    0xfecdd3FF
#define C_ROSE_3                    0xfda4afFF
#define C_ROSE_4                    0xfb7185FF
#define C_ROSE_5                    0xf43f5eFF
#define C_ROSE_6                    0xe11d48FF
#define C_ROSE_7                    0xbe123cFF
#define C_ROSE_8                    0x9f1239FF
#define C_ROSE_9                    0x881337FF

// 

#define CE_GREY_9                    "{171717}"
#define CE_GREY_8                    "{262626}"
#define CE_GREY_7                    "{404040}"
#define CE_GREY_6                    "{525252}"
#define CE_GREY_5                    "{737373}"
#define CE_GREY_4                    "{A3A3A3}"
#define CE_GREY_3                    "{D4D4D4}"
#define CE_GREY_2                    "{E5E5E5}"
#define CE_GREY_1                    "{F5F5F5}"
#define CE_GREY_0                    "{FAFAFA}"

#define CE_RED_0                     "{fef2f2}"
#define CE_RED_1                     "{fee2e2}"
#define CE_RED_2                     "{fecaca}"
#define CE_RED_3                     "{fca5a5}"
#define CE_RED_4                     "{f87171}"
#define CE_RED_5                     "{ef4444}"
#define CE_RED_6                     "{dc2626}"
#define CE_RED_7                     "{b91c1c}"
#define CE_RED_8                     "{991b1b}"
#define CE_RED_9                     "{7f1d1d}"

#define CE_ORANGE_0                  "{fff7ed}"
#define CE_ORANGE_1                  "{ffedd5}"
#define CE_ORANGE_2                  "{fed7aa}"
#define CE_ORANGE_3                  "{fdba74}"
#define CE_ORANGE_4                  "{fb923c}"
#define CE_ORANGE_5                  "{f97316}"
#define CE_ORANGE_6                  "{ea580c}"
#define CE_ORANGE_7                  "{c2410c}"
#define CE_ORANGE_8                  "{9a3412}"
#define CE_ORANGE_9                  "{7c2d12}"

#define CE_AMBER_0                   "{fffbeb}"
#define CE_AMBER_1                   "{fef3c7}"
#define CE_AMBER_2                   "{fde68a}"
#define CE_AMBER_3                   "{fcd34d}"
#define CE_AMBER_4                   "{fbbf24}"
#define CE_AMBER_5                   "{f59e0b}"
#define CE_AMBER_6                   "{d97706}"
#define CE_AMBER_7                   "{b45309}"
#define CE_AMBER_8                   "{92400e}"
#define CE_AMBER_9                   "{78350f}"

#define CE_YELLOW_9                  "{713F12}"
#define CE_YELLOW_8                  "{854D0E}"
#define CE_YELLOW_7                  "{A16207}"
#define CE_YELLOW_6                  "{CA8A04}"
#define CE_YELLOW_5                  "{EAB308}"
#define CE_YELLOW_4                  "{FACC15}"
#define CE_YELLOW_3                  "{FDE047}"
#define CE_YELLOW_2                  "{FEF08A}"
#define CE_YELLOW_1                  "{FEF9C3}"
#define CE_YELLOW_0                  "{FEFCE8}"

#define CE_LIME_0                    "{f7fee7}"
#define CE_LIME_1                    "{ecfccb}"
#define CE_LIME_2                    "{d9f99d}"
#define CE_LIME_3                    "{bef264}"
#define CE_LIME_4                    "{a3e635}"
#define CE_LIME_5                    "{84cc16}"
#define CE_LIME_6                    "{65a30d}"
#define CE_LIME_7                    "{4d7c0f}"
#define CE_LIME_8                    "{3f6212}"
#define CE_LIME_9                    "{365314}"

#define CE_GREEN_0                   "{f0fdf4}"
#define CE_GREEN_1                   "{dcfce7}"
#define CE_GREEN_2                   "{bbf7d0}"
#define CE_GREEN_3                   "{86efac}"
#define CE_GREEN_4                   "{4ade80}"
#define CE_GREEN_5                   "{22c55e}"
#define CE_GREEN_6                   "{16a34a}"
#define CE_GREEN_7                   "{15803d}"
#define CE_GREEN_8                   "{166534}"
#define CE_GREEN_9                   "{14532d}"

#define CE_EMERALD_0                 "{ecfdf5}"
#define CE_EMERALD_1                 "{d1fae5}"
#define CE_EMERALD_2                 "{a7f3d0}"
#define CE_EMERALD_3                 "{6ee7b7}"
#define CE_EMERALD_4                 "{34d399}"
#define CE_EMERALD_5                 "{10b981}"
#define CE_EMERALD_6                 "{059669}"
#define CE_EMERALD_7                 "{047857}"
#define CE_EMERALD_8                 "{065f46}"
#define CE_EMERALD_9                 "{064e3b}"

#define CE_TEAL_0                    "{f0fdfa}"
#define CE_TEAL_1                    "{ccfbf1}"
#define CE_TEAL_2                    "{99f6e4}"
#define CE_TEAL_3                    "{5eead4}"
#define CE_TEAL_4                    "{2dd4bf}"
#define CE_TEAL_5                    "{14b8a6}"
#define CE_TEAL_6                    "{0d9488}"
#define CE_TEAL_7                    "{0f766e}"
#define CE_TEAL_8                    "{115e59}"
#define CE_TEAL_9                    "{134e4a}"

#define CE_CYAN_0                    "{ecfeff}"
#define CE_CYAN_1                    "{cffafe}"
#define CE_CYAN_2                    "{a5f3fc}"
#define CE_CYAN_3                    "{67e8f9}"
#define CE_CYAN_4                    "{22d3ee}"
#define CE_CYAN_5                    "{06b6d4}"
#define CE_CYAN_6                    "{0891b2}"
#define CE_CYAN_7                    "{0e7490}"
#define CE_CYAN_8                    "{155e75}"
#define CE_CYAN_9                    "{164e63}"

#define CE_SKY_0                     "{f0f9ff}"
#define CE_SKY_1                     "{e0f2fe}"
#define CE_SKY_2                     "{bae6fd}"
#define CE_SKY_3                     "{7dd3fc}"
#define CE_SKY_4                     "{38bdf8}"
#define CE_SKY_5                     "{0ea5e9}"
#define CE_SKY_6                     "{0284c7}"
#define CE_SKY_7                     "{0369a1}"
#define CE_SKY_8                     "{075985}"
#define CE_SKY_9                     "{0c4a6e}"

#define CE_BLUE_0                    "{eff6ff}"
#define CE_BLUE_1                    "{dbeafe}"
#define CE_BLUE_2                    "{bfdbfe}"
#define CE_BLUE_3                    "{93c5fd}"
#define CE_BLUE_4                    "{60a5fa}"
#define CE_BLUE_5                    "{3b82f6}"
#define CE_BLUE_6                    "{2563eb}"
#define CE_BLUE_7                    "{1d4ed8}"
#define CE_BLUE_8                    "{1e40af}"
#define CE_BLUE_9                    "{1e3a8a}"

#define CE_INDIGO_0                  "{eef2ff}"
#define CE_INDIGO_1                  "{e0e7ff}"
#define CE_INDIGO_2                  "{c7d2fe}"
#define CE_INDIGO_3                  "{a5b4fc}"
#define CE_INDIGO_4                  "{818cf8}"
#define CE_INDIGO_5                  "{6366f1}"
#define CE_INDIGO_6                  "{4f46e5}"
#define CE_INDIGO_7                  "{4338ca}"
#define CE_INDIGO_8                  "{3730a3}"
#define CE_INDIGO_9                  "{312e81}"

#define CE_VIOLET_0                  "{f5f3ff}"
#define CE_VIOLET_1                  "{ede9fe}"
#define CE_VIOLET_2                  "{ddd6fe}"
#define CE_VIOLET_3                  "{c4b5fd}"
#define CE_VIOLET_4                  "{a78bfa}"
#define CE_VIOLET_5                  "{8b5cf6}"
#define CE_VIOLET_6                  "{7c3aed}"
#define CE_VIOLET_7                  "{6d28d9}"
#define CE_VIOLET_8                  "{5b21b6}"
#define CE_VIOLET_9                  "{4c1d95}"

#define CE_PURPLE_0                  "{faf5ff}"
#define CE_PURPLE_1                  "{f3e8ff}"
#define CE_PURPLE_2                  "{e9d5ff}"
#define CE_PURPLE_3                  "{d8b4fe}"
#define CE_PURPLE_4                  "{c084fc}"
#define CE_PURPLE_5                  "{a855f7}"
#define CE_PURPLE_6                  "{9333ea}"
#define CE_PURPLE_7                  "{7e22ce}"
#define CE_PURPLE_8                  "{6b21a8}"
#define CE_PURPLE_9                  "{581c87}"

#define CE_FUCHSIA_0                 "{fdf4ff}"
#define CE_FUCHSIA_1                 "{fae8ff}"
#define CE_FUCHSIA_2                 "{f5d0fe}"
#define CE_FUCHSIA_3                 "{f0abfc}"
#define CE_FUCHSIA_4                 "{e879f9}"
#define CE_FUCHSIA_5                 "{d946ef}"
#define CE_FUCHSIA_6                 "{c026d3}"
#define CE_FUCHSIA_7                 "{a21caf}"
#define CE_FUCHSIA_8                 "{86198f}"
#define CE_FUCHSIA_9                 "{701a75}"

#define CE_PINK_0                    "{fdf2f8FF}"
#define CE_PINK_1                    "{fce7f3FF}"
#define CE_PINK_2                    "{fbcfe8FF}"
#define CE_PINK_3                    "{f9a8d4FF}"
#define CE_PINK_4                    "{f472b6FF}"
#define CE_PINK_5                    "{ec4899FF}"
#define CE_PINK_6                    "{db2777FF}"
#define CE_PINK_7                    "{be185dFF}"
#define CE_PINK_8                    "{9d174dFF}"
#define CE_PINK_9                    "{831843FF}"

#define CE_ROSE_0                    "{fff1f2}"
#define CE_ROSE_1                    "{ffe4e6}"
#define CE_ROSE_2                    "{fecdd3}"
#define CE_ROSE_3                    "{fda4af}"
#define CE_ROSE_4                    "{fb7185}"
#define CE_ROSE_5                    "{f43f5e}"
#define CE_ROSE_6                    "{e11d48}"
#define CE_ROSE_7                    "{be123c}"
#define CE_ROSE_8                    "{9f1239}"
#define CE_ROSE_9                    "{881337}"
```

## Testing

<!--
Depending on whether your package is tested via in-game "demo tests" or
y_testing unit-tests, you should indicate to readers what to expect below here.
-->

To test, simply run the package:

```bash
sampctl package run
```
