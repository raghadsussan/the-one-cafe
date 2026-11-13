# The One Where You Get Things Done — Edition 06

An unofficial Friends-inspired vintage café built with HTML, CSS and JavaScript. No build, package install, account or API key required. All paths are relative, suitable for GitHub Pages.

## What's new

- The original floating countdown layout is restored at the bottom of the screen, with olive-green and brass coloring. It appears when a session starts, remains while paused or complete, and hides on reset. Pause/Resume and Settings work from the floating clock; its state is shared with the timer dialog. The café wall is unobstructed again.
- Twelve curated episodes, with season, mood and character selectors, plus a full browsable shelf. Season is a strict filter; mood/character matching chooses the best candidates within that season. Mood and character tags are editorial. Closest matches are labelled. Single strongest matches can repeat; ties avoid the last selection.
- Thirteen sound options: rain, brown noise, café hum/cups, city hush, fireplace, plucked strings, jazz-style keys/bass, lo-fi beat, soft piano, ambient chords, vinyl crackle, wind and espresso steam. Music choices are original synthesized 32-second loops, not recorded performances or commercial songs. The other options loop after 12 seconds. A separate cup chime can play over ambience. Volume controls the audio; playback starts only on a click.

## Existing features

Custom study durations from 1–600 whole minutes and breaks from 1–180. Press Apply times to save. Choose Study or Break manually. Applying times, switching sessions or resetting starts that duration again in a stopped state. Absolute deadlines avoid accumulating timer drift during background throttling; no guaranteed alarm while the device is asleep. Reloading closes the active session.

Tasks and preferences are browser-local. Their storage keys have been preserved. They do not automatically migrate between folders when using file://, devices, or between a local preview and GitHub Pages. Copy important task text before moving the project. Data clears if site storage is removed.

Clear/rain/snow/fog select AI-created still images. Afternoon brightness is reduced and the palette is warm parchment. Night mode is separately selectable. No actual weather service or location permission is used.

The extra illustrated mug cycles original fan-inspired jokes. Episode source pages can contain spoilers even though the descriptions in this site are spoiler-light. No episode videos are embedded.

The optional audio picker plays a file from your device using a local object URL; it is not uploaded or bundled into the site. Choose files you have permission to use. Select the file again after refreshing. Personal audio and the main ambience pause each other.

## Files

Keep index.html, style.css, app.js and the whole assets folder together. SOURCES.md records provenance. .nojekyll is included for static hosting. Edit colors and clock placement in style.css, episode/audio logic in app.js, and page content in index.html.

## Verification

JavaScript syntax and isolated functional checks passed: custom timing, synchronized main/dialog displays, pause/resume, completion, validation, weather asset selection, joke rotation, all thirteen audio play/stop paths, all season filters and the twelve-item shelf. Four music buffers were checked for finite, non-silent, bounded samples. Real browser visual layout and listening QA could not be completed in this environment; review on your Mac before publishing. No public deployment was performed.

## تشغيل النسخة على الماك — مرحلة واحدة

1. نزّلي The-One-Cafe-Edition06.zip وافتحيه بضغطتين.
2. افتحي المجلد الجديد the-one-cafe-edition06.
3. اضغطي كليك يمين على index.html ثم Open With ثم Safari أو Google Chrome.
4. تأكدي من وجود EDITION 06 · VINTAGE DETAILS بأسفل الصفحة. شغّلي المؤقّت وأغلقي نافذته؛ ستظهر الساعة الخضراء أسفل الشاشة.

لا تمحي النسخة القديمة قبل التجربة. مجلد جديد ممكن يعني أن المهام القديمة لا تظهر؛ تبقى في النسخة القديمة حسب المتصفح. كل الصور المطلوبة موجودة داخل assets ولا تحتاج تنزيل إضافي.

## Edition 06 typography

Clock, task list, audio controls and episode controls now use a vintage system-font stack: American Typewriter (when available, including many Macs), then Courier New/Courier/monospace. Panel headings use Baskerville/Palatino/Georgia. No remote font request or extra asset is required. Font appearance depends on installed system fonts; native dropdown rendering also depends on the browser. Other features and the café image are unchanged. Visual browser QA was unavailable for this revision; code checks passed.
