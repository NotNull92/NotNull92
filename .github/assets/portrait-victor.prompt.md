# Victor portrait and profile assets

Created 2026-10-26 with built-in image_gen, following Claude implementation design A3.

Identity reference: user-supplied portrait (kept outside repository). Style reference: studio-cover.png.

## Prompt
Portrait bust illustration, same anime film style and warm/cool evening lighting as the studio banner. Preserve the real person’s recognizable face structure, short black hair and broad shoulders. Adult man, charcoal collared jacket and light shirt, calm thoughtful expression, three-quarter view towards the right. Warm amber key light from lower left and cool blue rim from upper right. Deep navy #0F1B33 background, thin warm gold #D9A441 rounded-square frame. No text, logos, weapons or fantasy armor.

## Processing
Generated master retained outside repo; portrait resized to 280×280 with Lanczos and a 256-color palette: 50,535 bytes. Banner PNG preserved; JPEG quality 85 optimized derivative: 333,407 bytes. Social preview is a 1280×640 right-aligned crop per Claude design.

## Actual project assets
User authorized public screenshots and character icons on 2026-10-26.
- icon-monstel.png: monstel/assets/sprites/mons.png, atlas mon_0_idle, padded to32×32 then nearest-neighbor2×.
- icon-golem.png: golemsculptor/assets/golems/golem_normal/golem_combat_sheet.png, idle frame (0,0,32,32), nearest-neighbor2×.
- shot-monstel-01.png: monstel/qa/tutorial/2026-10-08-assets/sky-sprite-new-hotel.png. Existing QA capture, not certified as current build.
- shot-golem-01.png: golemsculptor/docs/qa/cocos-migration/html-777-after-fire.png. Existing QA capture, not certified as current build.
- Screenshots preserve the full scene and aspect ratio with proportional resizing, 12px navy padding and gold corner marks. No generated gameplay.
- poster-hera-godot.jpg: original thumbnail for https://youtu.be/1YSc7_Q_Djc, from https://i.ytimg.com/vi/1YSc7_Q_Djc/hqdefault.jpg with a play glyph. Promotional video thumbnail, not a gameplay capture.
- divider.svg and monogram.svg: authored directly by Claude; static vector decoration.
