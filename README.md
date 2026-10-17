# Exponential Money IQ VideoExpress Workflow

A personal fork of the VideoExpress narrated story workflow, adapted for long-form 2D finance education. The upstream project remains unchanged.

## Defaults

- Format: Landscape 16:9, 2D stickman illustrations.
- Main character: Daniel, with the same saved master image across finance episodes. His design is a white circular head, expressive black eyes and eyebrows, charcoal-blue sweater, teal trousers, and dark shoes.
- Narrator: Christopher's system voice unless the user chooses another available voice.
- Project: one VideoExpress project per episode, with public-gallery sharing off.

## Produce a finance video

1. Read [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) and the matching example in [examples](examples/).
2. Keep Daniel's approved master as Reference Photo 1. Select the same location reference as Reference Photo 2 whenever the scene returns to that setting.
3. Plan the narration and visual beats before generation. Preserve Daniel's face, proportions, clothing, colours, and screen geography.
4. For a 10-minute episode, aim for 9:45–10:15 of measured final runtime. Draft about 1,300–1,400 spoken words, then measure the audio and adjust the script to fit naturally.
5. Use VideoExpress's built-in Text to Speech panel for long narration segments within the visible character limit. Keep the generated audio in VideoExpress and place each segment with its matching visuals on the same timeline. Do not use outside voice services or downloaded audio.
6. Cover the full narration with varied scenes and graphics. Do not stretch a short clip or repeat speech to claim a longer runtime.
7. Auto Align, check the total duration and timeline order, save the project, export an MP4, and verify that it opens.

## Finance standards

Present the topic as general education. Do not suggest that habits guarantee wealth or that people with less money simply lack discipline. Recognise that income, opportunity, health, family responsibilities, and economic conditions affect outcomes. Avoid individual investment, tax, and debt instructions. Explain that investments can lose value and use current official sources for specific claims.

## Files

- [System prompt](SYSTEM_PROMPT.md) contains the reusable agent instructions.
- [10-minute money habits example](examples/finance-money-habits-10min.md) provides a sample outline and production plan.
- [Acceptance checklist](evals/acceptance-checklist.md) defines the completion checks.
- Existing story examples remain available for general continuity and animation guidance.

The workflow should not report a video as complete until the saved project, measured runtime, and exported file have been checked. Keep scripts and intermediate candidates internal unless the user asks to see them.
