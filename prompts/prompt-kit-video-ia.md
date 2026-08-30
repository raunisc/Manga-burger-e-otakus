# KIT DE PROMPTS PARA IA DE VÍDEO — BURGER & OTAKUS
### Versão 1.0 · baseada no Episódio 1 · para uso com Veo, Kling, Runway Gen-4, Hailuo/MiniMax, Pika, Luma etc.

> **Como usar:** (1) anexe a *model sheet* do personagem (`../modelos/*.png`) como imagem de referência/primeiro frame sempre que possível; (2) cole o **BLOCO DE ESTILO GLOBAL** + o **BLOCO DO PERSONAGEM** + o **PROMPT DE CENA** no campo de prompt; (3) use o *negative prompt* quando a ferramenta permitir. Prompts em inglês rendem mais nas IAs de vídeo; os textos "na tela" (SISTEMA, placas) devem ser pedidos em português, entre aspas.

---

## 0. NEGATIVE PROMPT (universal)

```
3D render, CGI, photorealism, live action, chibi, western comic style, pastel colors, flat lighting, extra fingers, deformed hands, watermark, signature, text artifacts, blurry face, inconsistent clothing, modern streetwear, colorful bright daytime sky
```

---

## 1. BLOCO DE ESTILO GLOBAL (cole sempre no início do prompt)

```
Full-color seinen-shonen anime manga aesthetic, painterly digital art with dense hatching and film grain, high contrast cinematic lighting, deep brown-black shadows (#0A0806), dominant amber-orange energy glow (#F59E2D / #E86A17) against dark backgrounds, strong rim light, dramatic chiaroscuro, wet neon cyberpunk city at night with rain, subtle vignette on every shot, hand-drawn lineart look, dramatic camera angles, epic shonen atmosphere. All on-screen text (system windows, signs, onomatopoeia) written in Portuguese.
```

---

## 2. BLOCOS DE PERSONAGEM (copie o do personagem da cena)

### 2.1 RAILDO — base (civil)
```
RAILDO, 16-year-old anime boy, lean wiry build (1.65 m), light tan skin, short messy spiky black hair with jagged fringe over his forehead, sharp dark-brown eyes with faint tired eye-bags, determined exhausted expression. Wears EXACTLY: black short-sleeve work t-shirt with a red-and-yellow burger-and-lightning-bolt logo "BURGER & OTAKUS" on the chest, dark brown waist apron, black fingerless gloves, black pants. Moves like a hard worker: quick, economical, tense shoulders.
```

### 2.2 RAILDO — forma desperta (Núcleo ativo)
```
RAILDO in AWAKENED form: same boy (spiky black hair, dark brown eyes now glinting amber), black t-shirt and black fingerless gloves; glowing amber energy filaments swirling around both forearms, a bright circular rune sigil burning on his inner forearm, a glowing ring of golden light floating at the center of his chest (the NÚCLEO), floating orange ember particles around him, a massive flame aura rising behind his shoulders, ground beneath him glowing with an amber grid like a hot griddle. Confident smirk, battle-ready stance.
```

### 2.3 LUNA
```
LUNA, mysterious anime girl (16-17), slim, pale skin, very long straight dark-purple hair with straight bangs, intense violet eyes, serious guarded expression. Wears EXACTLY: dark long-sleeved jacket with a small purple emblem on the chest over a dark top, dark shorts over black leggings; a glowing purple alchemical sun sigil on her forearm. Cool purple ambient glow around her; she appears quietly in doorways, calm and unafraid.
```

### 2.4 O CAÇADOR MISTERIOSO
```
THE MYSTERIOUS HUNTER, tall man around 40, shoulder-length messy black hair, short dark beard, sharp tired eyes, knowing half-smile. Long black coat over a dark shirt and dark pants, hands in pockets; a faintly glowing amber sun-like sigil tattoo on his wrist. Walks slowly through rain without hurrying; presence feels dangerous and calm.
```

### 2.5 CRIATURAS DE SOMBRA (comum)
```
SHADOW CREATURE: a monster made of living black tar-smoke and cracked volcanic plates, molten orange energy veins glowing through the cracks, blazing orange eyes, oversized mouth full of jagged teeth, long clawed arms, about 2 meters tall, crawling forward with hostile jerky movement, embers rising off its body.
```

### 2.6 CRIATURA-CHEFE
```
BOSS SHADOW BEAST: 4.5-meter hulking monstrous shadow creature, massively muscled, body of black smoke and cracked magma plating with bright molten orange veins, two blazing orange eyes, huge fanged maw, knuckle-walking like a gorilla-beast, each step cracking the stone floor, roar shaking dust from the walls, embers exploding off its back.
```

### 2.7 JANELA DO SISTEMA (elemento de tela)
```
GAME-LIKE SYSTEM WINDOW: floating retro-futuristic golden frame made of layered hexagonal tech lines, glowing pixel/LED font, on pure black background with falling amber digital rain. On-screen text in Portuguese, exactly: "SISTEMA: NÚCLEO DESPERTADO."
```
*(substitua o texto entre aspas pela mensagem canônica da cena: "PROVA CONCLUÍDA." / "HABILIDADE ADQUIRIDA: DOMÍNIO DA CHAPA." / "HABILIDADE OCULTA DETECTADA: FOME ABSOLUTA." / "Núcleo reconhecido. Compatibilidade: 97%.")*

---

## 3. CENÁRIOS-CARDEAIS (anexe ao prompt quando a cena ocorrer neles)

```
[LOJA - EXT] Rainy neon cyberpunk street at night, small burger restaurant "BURGER & OTAKUS" with glowing red-and-yellow neon burger-and-lightning sign, brick facade, anime posters on the windows, wet asphalt reflecting neon, passersby with umbrellas, cool blue tones contrasting with the warm amber of the shop.
[LOJA - INT] Cozy dark burger joint interior: brick walls, anime posters, red stools, menu board, counter with grill, warm amber pendant light, rain visible through the window, chalkboard "RANKING DOS CAÇADORES DA CIDADE" on the wall.
[PORTAL] Dark kitchen floor cracking open with incandescent orange light veins (SFX: THUM), debris floating, heat shimmer, an impossible dark corridor revealed below.
[DIMENSÃO] Gigantic circular ancient chamber, walls carved with glowing rune circles, stone altar at the center lit by a single blue star of light, candles, oppressive darkness beyond a ring of light, symmetrical wide shots.
```

---

## 4. PLANTILHAS DE CENA (prompt final = 1 + personagem + 3 + cena)

### 4.1 Estabelecimento (abertura de episódio)
```
Slow cinematic dolly-in through heavy rain toward a neon burger restaurant sign at night, crowd with umbrellas passing by, reflections on wet asphalt, a lone hooded figure watching from a dark alley, ominous mood, [BLOCO DE ESTILO], [LOJA - EXT], ambient rain sound, low thunder.
```

### 4.2 Rotina na loja (tom leve/comédia)
```
Handheld medium shot, [RAILDO base] flipping burgers on a hot grill, steam rising, he sighs and wipes sweat with his forearm, warm amber light, [LOJA - INT], [BLOCO DE ESTILO], cozy lo-fi kitchen ambience with rain outside.
```

### 4.3 Abertura do portal
```
Low angle on the kitchen floor: cracks of blazing orange light spread like lightning (onomatopoeia THUM in bold orange letters), tiles levitate, [RAILDO base] steps back shielding his eyes, camera shakes, [PORTAL], [BLOCO DE ESTILO], deep rumble and glass tremble sound.
```

### 4.4 A Escolha dos Caminhos
```
Wide symmetrical shot inside the ancient circular chamber, [RAILDO base] small before the stone altar, three glowing runic circles materialize in the air labeled in Portuguese "[ POTÊNCIA ]" orange, "[ AGILIDADE ]" green, "[ EQUILÍBRIO ]" blue, a blue star of light hovering above the altar, [DIMENSÃO], [BLOCO DE ESTILO], mysterious choir drone.
```

### 4.5 Despertar do Núcleo
```
Slow push-in on [RAILDO desperto]: amber energy filaments wrap around his arms, the rune sigil ignites on his forearm, a golden ring of light bursts at his chest, embers spiral upward, his eyes flash amber, camera orbits 180°, [DIMENSÃO], [BLOCO DE ESTILO], power-up sound design with deep bass hit.
```

### 4.6 Combate (padrão shonen)
```
Dynamic action sequence, dutch angles and speedlines: [CRIATURA-CHEFE] charges and smashes a wall (onomatopoeia BOOOM in orange letters), [RAILDO desperto] slides under the arm and slams his palm on the floor shouting "DOMÍNIO DA CHAPA!", a giant glowing griddle-grid erupts beneath the beast, he concentrates all energy in one fist shouting "FOME ABSOLUTA!" and punches — screen-filling orange explosion (onomatopoeia BOOOOOOOOOM), then silence and falling embers, [DIMENSÃO], [BLOCO DE ESTILO], heavy impact SFX then sudden silence with ember crackle.
```

### 4.7 Revelação da Luna (padrão mistério)
```
Static night interior shot of the dark closed restaurant, door opens, cold blue street light cuts inside, [LUNA] stands in the doorway silhouetted, rain behind her, purple sigil glowing faintly on her forearm, [RAILDO base] turns startled, camera slow push-in on her violet eyes, [LOJA - INT], [BLOCO DE ESTILO], door chime and rain sound.
```

---

## 5. CHECKLIST DE CONSISTÊNCIA (antes de gerar cada vídeo)

- [ ] **Balão do lado do falante, cauda na boca de quem fala** (nunca sobre o ouvinte); ordem de leitura mantida (fala 1 acima da fala 2 do mesmo lado).
- [ ] **Física/gravidade:** nenhum objeto flutuando sem mão segurando ou sustentação visível no mundo da história (dispositivos, armas, comida sempre em contato com personagem/superfície).
- [ ] **Continuidade de distância:** proximidade entre personagens e criaturas coerente entre quadros consecutivos da mesma cena.
- [ ] Model sheet do personagem anexada como referência?
- [ ] Roupa exata descrita (logo, avental, luvas sem dedos / jaqueta com emblema)?
- [ ] Cor da energia correta? (âmbar/laranja = Raildo & Sistema · roxo = Luna · azul = Equilíbrio/altar)
- [ ] Sigilos nas posições canônicas? (Raildo: antebraço + anel no peito · Luna: antebraço · Misterioso: pulso)
- [ ] Texto de tela em português e entre aspas?
- [ ] Iluminação do cenário-caráter certa? (loja = âmbar quente · rua = azul frio · dimensão = preto + laranja · Luna = azul + roxo)
- [ ] SFX em onomatopeia laranja com contorno escuro, em caps?
- [ ] Sem sangue humano; criaturas dissolvem em brasas.

---

## 6. COMO AMPLIAR (Episódio 2+)

Sempre que um personagem novo aparecer nas páginas enviadas:
1. Criar model sheet nova em `../modelos/` (frente/perfil/costas + expressões + paleta).
2. Adicionar um bloco de personagem aqui (seção 2.x) no mesmo formato.
3. Registrar no `../analise/episodio-N.md` (ficha + regras de continuidade).
4. Se a habilidade for nova: definir nome em PT-BR + texto exato da janela do Sistema.
