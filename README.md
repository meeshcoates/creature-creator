# Creature Creator - Art Reference Tool

A lightweight, single-file HTML app that helps artists design fictional creatures by mixing and matching body parts from different animals, dinosaurs, mythical creatures, fictional beings, aliens, deep sea creatures, and weird bugs.

**Live demo:** [meeshcoates.github.io/creature-creator](https://meeshcoates.github.io/creature-creator/)

## How It Works

1. **Toggle categories** on/off to choose which creature pools are available
2. **Pick creatures** for each body part using the autocomplete dropdowns, or hit the dice button for random picks
3. **Lock slots** you like (padlock icon) so they survive a "Randomize All"
4. **Hit Generate** to fetch reference images from Wikipedia / Wikimedia Commons
5. **Click cards** to reveal/hide images one at a time, or use Reveal All / Hide All
6. **Click the magnifying glass** on any card to open a Google Images search tailored to that specific body part (e.g. "owl eyes close up")
7. **Copy AI Prompt** at the bottom builds a ready-to-paste prompt for Gemini, ChatGPT, etc.

No API keys, no install, no dependencies just open the HTML file in a browser.

## Body Part Slots

| Slot | Label | Google Search Terms | AI Prompt Phrasing |
|------|-------|--------------------|--------------------|
| `base` | Base Animal | *(general)* | the overall body shape and size of a |
| `head` | Head | head face | the head of a |
| `ears` | Ears | ears close up | the ears of a |
| `eyes` | Eyes | eyes close up | the eyes of a |
| `nose` | Nose / Snout | nose snout close up | the nose/snout of a |
| `body` | Body / Torso | body torso | the torso of a |
| `front` | Front Legs / Arms | front legs arms | the front legs/arms of a |
| `back` | Back Legs | back legs hind legs | the back legs of a |
| `feet` | Feet / Paws / Hooves | feet paws hooves claws close up | the feet/paws of a |
| `tail` | Tail | tail | the tail of a |
| `coat` | Coat / Skin / Scales | fur skin scales texture close up | the skin/coat texture of a |
| `color` | Colour / Pattern | colour pattern markings | the colour and pattern of a |
| `wings` | Wings (optional) | wings | the wings of a |
| `extra` | Extra Feature | unique features | a unique feature from a |

## Creature Categories

### Animals (160 creatures)
The standard animal kingdom; mammals, birds, reptiles, amphibians, fish, and invertebrates. Includes **Human** for mixing human features into creature designs.

<details>
<summary>Full list</summary>

Alligator, Alpaca, Ant, Anteater, Antelope, Armadillo, Axolotl, Baboon, Badger, Bat, Bear, Beaver, Beetle, Bison, Boar, Buffalo, Butterfly, Camel, Capybara, Caribou, Cat, Caterpillar, Chameleon, Cheetah, Chicken, Chimpanzee, Chinchilla, Cobra, Cockroach, Crab, Crane, Crocodile, Crow, Deer, Dingo, Dog, Dolphin, Donkey, Dragonfly, Duck, Eagle, Echidna, Eel, Elephant, Elk, Emu, Falcon, Ferret, Flamingo, Fly, Fox, Frog, Gazelle, Gecko, Giraffe, Goat, Goose, Gorilla, Grasshopper, Grizzly Bear, Hamster, Hare, Hawk, Hedgehog, Hippopotamus, Hornet, Horse, Human, Hummingbird, Hyena, Iguana, Impala, Jackal, Jaguar, Jellyfish, Kangaroo, Koala, Komodo Dragon, Ladybug, Lemur, Leopard, Lion, Lizard, Llama, Lobster, Lynx, Macaw, Mandrill, Manta Ray, Mantis, Meerkat, Moose, Moth, Mouse, Narwhal, Newt, Octopus, Opossum, Orangutan, Ostrich, Otter, Owl, Ox, Panda, Pangolin, Panther, Parrot, Peacock, Pelican, Penguin, Pig, Platypus, Polar Bear, Porcupine, Praying Mantis, Puffin, Python, Quail, Rabbit, Raccoon, Ram, Rat, Rattlesnake, Raven, Red Panda, Rhinoceros, Rooster, Salamander, Salmon, Scorpion, Seahorse, Seal, Shark, Sheep, Sloth, Snail, Snake, Snow Leopard, Spider, Squid, Squirrel, Starfish, Stingray, Swan, Tapir, Tiger, Toad, Toucan, Turkey, Turtle, Vulture, Walrus, Wasp, Weasel, Whale, Wolf, Wolverine, Wombat, Woodpecker, Yak, Zebra
</details>

### Dinosaurs (28 creatures)
Prehistoric reptiles. Images prioritise paleoart illustrations/reconstructions over fossil photos via Wikimedia Commons search.

<details>
<summary>Full list</summary>

Allosaurus, Ankylosaurus, Apatosaurus, Archaeopteryx, Brachiosaurus, Carnotaurus, Compsognathus, Deinonychus, Dilophosaurus, Diplodocus, Gallimimus, Giganotosaurus, Iguanodon, Megalosaurus, Mosasaurus, Pachycephalosaurus, Parasaurolophus, Plesiosaur, Pteranodon, Pterodactyl, Quetzalcoatlus, Spinosaurus, Stegosaurus, Therizinosaurus, Triceratops, Tyrannosaurus Rex, Utahraptor, Velociraptor
</details>

### Mythical Creatures (35 creatures)
Creatures from mythology and folklore. Images come from Wikipedia articles (which typically have paintings/illustrations) rather than Wikimedia Commons search, which proved unreliable for mythological subjects.

<details>
<summary>Full list</summary>

Basilisk, Behemoth, Centaur, Cerberus, Chimera, Cockatrice, Cyclops, Dragon, Fenrir, Gargoyle, Griffin, Harpy, Hippogriff, Hydra, Jackalope, Kelpie, Kraken, Leviathan, Manticore, Medusa, Minotaur, Naga, Nemean Lion, Pegasus, Phoenix, Qilin, Roc, Satyr, Sea Serpent, Siren, Sphinx, Thunderbird, Unicorn, Wendigo, Wyvern, Yeti
</details>

### Fiction / Fantasy (29 creatures)
Creatures from literature, film, TV, and games. Lovecraft, Tolkien, Harry Potter, Godzilla, and more. Like mythical creatures, images come from Wikipedia articles directly.

<details>
<summary>Full list</summary>

**Lovecraft:** Shoggoth, Cthulhu, Deep One, Elder Thing, Mi-Go, Nyarlathotep
**Tolkien:** Balrog, Ent, Fellbeast, Shelob, Warg
**Harry Potter:** Basilisk, Hippogriff, Thestral, Acromantula, Niffler, Bowtruckle
**Film & TV:** Godzilla, King Kong, Mothra, Cloverfield Monster, Demogorgon, Graboid, Kaiju
**Games:** Chocobo, Deathclaw, Creeper, Enderman
**Literature:** Sandworm
</details>

### Aliens (28 creatures)
Extraterrestrials and alien creatures from sci-fi. Images come from Wikipedia articles directly.

<details>
<summary>Full list</summary>

**Film:** Xenomorph, Facehugger, Predator, E.T., Groot, Jabba the Hutt
**Star Wars:** Rancor, Sarlacc, Tauntaun, Wampa, Krayt Dragon
**Star Trek:** Tribble, Gorn, Tholian
**Doctor Who:** Dalek, Weeping Angel, Ood, Zygon
**Film & TV:** Martian, Prawns, Predaking
**Literature:** Thoat, Banth, Pierson's Puppeteer
**Games:** Metroid, Elite, Headcrab, Hydralisk
**Archetypes:** Grey Alien, Reptilian, Insectoid Alien
</details>

### Deep Sea (38 creatures)
Bizarre deep-ocean creatures. Real animals with real photos — no illustration preference needed.

<details>
<summary>Full list</summary>

Anglerfish, Barreleye, Blobfish, Blue-Ringed Octopus, Chambered Nautilus, Chimaera, Coconut Octopus, Colossal Squid, Cookiecutter Shark, Dumbo Octopus, Fangtooth, Firefly Squid, Frilled Shark, Giant Isopod, Giant Spider Crab, Glass Octopus, Glass Squid, Goblin Shark, Greenland Shark, Gulper Eel, Hagfish, Hatchetfish, Horseshoe Crab, Leafy Sea Dragon, Mantis Shrimp, Mimic Octopus, Nautilus, Oarfish, Pyrosome, Sea Angel, Sea Cucumber, Sea Pig, Sea Spider, Siphonophore, Stoplight Loosejaw, Vampire Squid, Viperfish, Yeti Crab
</details>

### Weird Bugs (31 creatures)
The strangest insects and arachnids. Real animals with real photos.

<details>
<summary>Full list</summary>

Atlas Moth, Assassin Bug, Brazilian Treehopper, Bombardier Beetle, Devil's Flower Mantis, Dung Beetle, Giant Weta, Giraffe Weevil, Glowworm, Goliath Beetle, Goliath Birdeater, Hercules Beetle, Hickory Horned Devil, Jewel Beetle, Leaf Insect, Luna Moth, Orchid Mantis, Puss Moth Caterpillar, Rhinoceros Beetle, Rosy Maple Moth, Saddleback Caterpillar, Scorpionfly, Spiny Flower Mantis, Spiny Orb Weaver, Stick Insect, Thorn Bug, Titan Beetle, Venezuelan Poodle Moth, Walking Leaf, Wheel Bug, Whip Scorpion
</details>

## How Image Search Works

The app fetches images from Wikipedia and Wikimedia Commons using their free, no-auth APIs. This is trickier than it sounds because of disambiguation (e.g. "Turkey" the country vs the bird, "Python" the language vs the snake, "Rancor" the emotion vs the Star Wars creature).

### Search strategy

1. **Dinosaurs only:** Search Wikimedia Commons first for paleoart (terms like "restoration", "illustration", "reconstruction") to avoid fossil/skeleton photos
2. **Wikipedia REST API** (`/api/rest_v1/page/summary/{title}`) — tries multiple disambiguation variants in order:
   - Override mapping (if one exists, e.g. `Turkey` -> `Turkey_(bird)`)
   - `Name_(animal)`, `Name_(bird)`, `Name_(species)`, `Name_(genus)`
   - Plain `Name`
3. **Article validation** each result's extract text is checked for animal/creature keywords (mammal, species, mythology, fictional, etc.) and rejected if it matches non-creature topics (constellation, programming language, band, political, etc.)
4. **Wikipedia Search API fallback** searches for `"name animal species"` or `"name illustration reconstruction"` and scores top 5 results
5. **Last resort** Wikimedia Commons search with just the creature name

### Wikipedia overrides

Many creatures need explicit Wikipedia page mappings to avoid disambiguation issues. The `WIKI_OVERRIDES` object maps creature names to their correct Wikipedia article title. Some notable examples:

| Creature | Problem | Override |
|----------|---------|----------|
| Turkey | Returns the country | `Turkey_(bird)` |
| Python | Returns the programming language | `Python_(genus)` |
| Panda | Returns Panda oleosa (a plant) | `Giant_panda` |
| Rancor | Returns article about hatred | `Rancor_(Star_Wars)` |
| Hydra | Returns the constellation | `Hydra_(mythology)` |
| Creeper | Returns the plant | `Creeper_(Minecraft)` |
| Predator | Returns the film | `Yautja` |
| Dumbo Octopus | No exact article | `Grimpoteuthis` |
| Orchid Mantis | No exact article | `Hymenopus_coronatus` |
| Human | Returns "Lists of extinct species" | `Human_body` |

### Image rejection filters

Images are rejected if their URL or filename contains terms suggesting inappropriate or irrelevant content:

- **Fossils/specimens:** fossil, skeleton, skull, bone, museum, specimen, holotype
- **Microscopy:** microscop, microbe, bacteria, cell, electron
- **Maps/diagrams:** flag, logo, map, diagram, chart, graph
- **Astronomy:** constellation, star_chart, astro
- **Inappropriate:** rally, protest, nazi, supremac, charlottesville
- **Music:** band, album, concert, guitarist, vocalist, drummer

### Google Image search context

The magnifying glass link on each card opens a Google Images search with context-aware terms:

| Category | Search context added |
|----------|---------------------|
| Animals | `animal` |
| Human | *(none)* |
| Dinosaurs | `dinosaur` |
| Mythical | `mythology creature` |
| Fiction | `fictional creature` |
| Aliens | `alien creature sci-fi` |
| Deep Sea | `deep sea creature` |
| Weird Bugs | `insect bug` |

All searches also append `reference photo` to bias towards useful art reference images.

## Forking & Customisation

The entire app is a single `index.html` file. To add your own creatures:

1. **Add to the array** — find the relevant `const` array (e.g. `ANIMALS`, `FICTION`) and add your creature name in alphabetical order
2. **Add a Wikipedia override** (if needed) — add an entry to `WIKI_OVERRIDES` mapping your creature name to its Wikipedia article title. Test by visiting `https://en.wikipedia.org/wiki/Your_Article_Title` first
3. **If it's a new category** — add a new array, a toggle checkbox in the HTML, update `getActiveList()`, and optionally update `needsIllustration()` (for non-photographic creatures) and `imageSearchUrl()` (for the Google search context)

### Tips for adding creatures

- Always test the Wikipedia image by searching the REST API: `https://en.wikipedia.org/api/rest_v1/page/summary/Article_Title`
- If a creature name collides with something else (a band, a city, a programming language), you **must** add a `WIKI_OVERRIDES` entry
- For creatures with no Wikipedia image at all, consider removing them — the app will show "No photo found" which isn't useful
- Add reject keywords to `REJECT_KEYWORDS` or `COMMONS_REJECT` if you find inappropriate images slipping through

## Tech Stack

- Single HTML file with embedded CSS and JS
- Wikipedia REST API (no auth required)
- Wikimedia Commons API (no auth required)
- Google Images search links (opens in new tab)
- Hosted on GitHub Pages

## Credits

Built with [Claude Code](https://claude.ai/code) by Anthropic.

## License

MIT — do whatever you want with it.
