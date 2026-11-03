---
name: prn-melaka-2026-03_dira-six-ten-second-films
description: Reusable English editorial 60-second introduction skill for Khaidhirah Abu Zahar; six 1x4 storyboards each paired with one seamless 10-second vertical video, text-only Disney/Pixar-inspired original 3D character and external public-photo review.
---

# Dira — Character, Storyboard and Video Skill

**Person:** Khaidhirah Abu Zahar · **Nickname:** Dira · **Affiliation:** BN · **Seat:** N25 Rim · **As of:** 3 November 2026.

## Fixed production contract

- Exactly six **storyboard-image prompts**, each a *single 1×4 grid of four 9:16 portrait panels* (combined sheet 9:4).
- Exactly six **video prompts**, each animating its paired storyboard's four panels **into one 10-second 9:16 video** (four 2.5-second segments); six videos = one minute.
- All prompts, directions, narration and captions in **English**. No fictional speeches by the real person, endorsements or vote requests.
- Original **Disney/Pixar-inspired polished family-film 3D animation**, with independently designed human character proportions, not copied existing franchise characters.
- No reference photograph supplied to the generator. Each script contains a fully specified character design based on available observed photo features and flagged creative approximations.
- Before publication, inspect the [real photograph reference](https://international.astroawani.com/malaysia-news/kak-som-dira-abu-zahar-among-five-women-winners-melaka-332014) and assess the generated portrait's similarity. The original photo is linked, not copied. Use a generated master avatar as a *later* reference only if a consistent face is required; distinguish this from the text-only control.
- The full script is in [PROMPT.md](PROMPT.md). The photo description and link are in [PHOTO_REFERENCE.md](PHOTO_REFERENCE.md).

## Character identity lock

Malaysian woman in her forties, gently rounded oval face with softly tapered chin, smooth fair-to-light-tan complexion, expressive medium-dark brown eyes, delicate curved dark eyebrows, straight softly contoured nose, defined natural lips, warm neutral expression. A light pearl-grey hijab frames the face close to the forehead and falls in two symmetrical draped folds across the shoulders, covering all hair; no glasses. Wardrobe lock: Elegant modest dark navy baju kurung with small discreet embroidery near the upper chest, full-length matching skirt, simple closed-toe shoes; pearl-grey hijab kept identical.

Style: An original high-quality Disney/Pixar-inspired 3D family-film editorial aesthetic: rounded but recognizable human proportions, expressive eyes, subtle facial animation without speech, polished hair or hijab strands, precise fabric texture, soft cinematic global illumination, realistic but friendly textures, warm ivory, slate and muted teal colour grade, natural depth of field, 24fps fluid movement, respectful neutral mood. This is an ORIGINAL film-inspired illustration and NOT an existing film character, actual candidate footage, endorsement or political advertisement. Keep the same face geometry, eye spacing, hairstyle, glasses, head covering, facial hair, outfit and body proportions for all 24 panels.

## Commands

`START`: return the researched 24 beats and the full text-only master portrait prompt. `NEXT`: return exactly the next paired 4-panel storyboard + 10-second video prompt, advance one batch, repeat until Batch 6. `RETRY`: regenerate current batch without changing validated facts or character traits. `VERIFY`: review source facts. `HELP`: explain current stage. `NEW [candidate]`: change project and reset character identity. Never ask for an uploaded reference photo; showing a public link for review is sufficient.

## Fact ledger — source claims remain attributed

| Scene | Topic | Research statement | Source |
|---:|---|---|---|
| 1 | Candidate identity | Meet Dira. | [Source](https://election.bernama.com/prn/melaka/2026/penamaan/?detail=candidates) |
| 2 | Constituency | The constituency and its voters. | [Source](https://election.bernama.com/prn/melaka/2026/penamaan/?detail=candidates) |
| 3 | Election affiliation | Party affiliation on the ballot. | [Source](https://election.bernama.com/prn/melaka/2026/penamaan/?detail=candidates) |
| 4 | Professional background | A documented career background. | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 5 | Historical context | The record before nomination. | [Source](https://election.bernama.com/prn/melaka/2026/penamaan/?detail=candidates) |
| 6 | Past elected service | Earlier elected public service. | [Source](https://election.bernama.com/prn/melaka/2021/keputusan/statistik/) |
| 7 | Candidate-reported activity | `candidate_statement` | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 8 | Candidate-reported activity | `candidate_statement` | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 9 | Candidate-reported activity | `candidate_statement` | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 10 | Reported programme or state outcome | `reported_programme` | [Source](https://www.bernama.com/en/general/news.php?id=2571246) |
| 11 | Reported programme or state outcome | `reported_programme` | [Source](https://www.bernama.com/en/general/news.php?id=2571246) |
| 12 | Career and public record 6 | Previously worked as an actress. | [Source](https://www.thestar.com.my/news/nation/2021/11/10/from-election-volunteer-to-seat-contestant) |
| 13 | Career and public record 7 | Described earlier electoral volunteer experience. | [Source](https://www.thestar.com.my/news/nation/2021/11/10/from-election-volunteer-to-seat-contestant) |
| 14 | Electoral history | Represented BN in Rim, 2021. | [Source](https://www.thestar.com.my/news/nation/2021/11/10/from-election-volunteer-to-seat-contestant) |
| 15 | Electoral history | Won Rim by 1,327 votes. | [Source](https://election.bernama.com/prn/melaka/2021/keputusan/) |
| 16 | Candidate-reported activity | `candidate_statement` | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 17 | Evidence checkpoint | Review the original source. | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 18 | Programme context | Distinguish claims from completed work. | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 19 | Outcome versus plan | Programmes can involve multiple agencies. | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 20 | Attribution check | Check the reported dates and figures. | [Source](https://www.bernama.com/en/general/news.php?id=2571246) |
| 21 | Record recap | Public record overview. | [Source](https://prn.bernama.com/johor/news-en.php?id=2628647) |
| 22 | Source transparency | Source links support these statements. | [Source](https://election.bernama.com/prn/melaka/2026/penamaan/?detail=candidates) |
| 23 | Election information | Polling: November fourteenth. | [Source](https://www.spr.gov.my/km-prudunmelaka16/) |
| 24 | AI disclosure | AI-generated character and narration. | Editorial/production |

## Consistency & editorial QA

Test the same Prompt A in two independent, fresh text-only image-generation sessions, then compare face shape, eyes, eyebrows, hair/hijab, glasses, facial hair, complexion, proportions, outfit and accessories. A controlled reference-free match has **not** been demonstrated. Google Flow scene-to-scene identity has **not** been rendered or assessed. Correct factual mistakes, do not present announced projects as completed, distinguish personal acts from programme-wide outcomes, and publish an AI disclosure.
