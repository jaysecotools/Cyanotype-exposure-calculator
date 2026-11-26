Cyanotype Exposure Calculator

A practical, browser-based exposure calculator for traditional cyanotype printing. Estimate exposure times using sunlight or artificial UV light, adjust calculations to suit your materials and equipment, and fine-tune results through calibration and test-strip exposures.

Designed for cyanotype photographers, alternative-process enthusiasts, artists and anyone experimenting with UV-sensitive photographic printing.

Overview

Cyanotype exposure times can vary considerably depending on UV intensity, cloud cover, artificial light sources, lamp distance, paper sensitivity and the chemistry being used.

The Cyanotype Exposure Calculator provides a convenient way to estimate exposure times under different lighting conditions. It combines reference exposure data with adjustable calibration factors, allowing users to develop exposure settings that work with their own equipment and materials.

The application also includes an integrated exposure timer and test-strip helper to make practical experimentation easier.

Features

☀️ Sunlight Exposure Calculator

- Calculate estimated exposure times using the UV Index.
- Account for cloud cover through an adjustable cloud factor.
- Apply custom calibration factors to suit individual materials and working conditions.
- Receive warnings when UV levels are too low for reliable exposure estimates.

💡 Artificial UV Lamp Calculator

Supports several common UV light sources:

- BLB fluorescent tubes (15–20W).
- 365nm UV LED panels.
- 395nm UV LED panels.
- Mercury vapour lamps (400W).
- Metal halide lamps (400W).

Additional functionality includes:

- Adjustable lamp-to-print distance.
- Metric and imperial distance measurements.
- Distance-based exposure calculations using an inverse-square approximation.
- Individual calibration adjustments for different equipment and materials.

🎯 Calibration Profiles

- Create personalised exposure calibration profiles.
- Save and reuse settings for different papers, chemistry and coating techniques.
- Maintain separate calibration profiles for sunlight and artificial UV sources.
- Store profiles locally in the browser.

⏱️ Built-in Exposure Timer

- Automatically loads the calculated exposure time.
- Start, pause and resume exposure timing.
- Automatic completion notification.
- Optional audible completion alerts.
- Visual indication when the exposure period has finished.

📏 Test Strip Helper

Generate suggested exposure intervals around the calculated exposure time.

The helper provides:

- Half-time exposure.
- Three-quarter exposure.
- Estimated exposure.
- 1.25× exposure.
- 1.5× exposure.
- 2× exposure.

It also provides a progressive six-segment test-strip method to help identify the most suitable exposure duration.

How to Use

1. Select your exposure method

Choose either sunlight exposure or artificial UV lamp exposure.

2. Enter your conditions

For sunlight:

- Enter the current UV Index.
- Select the appropriate cloud-cover factor.
- Adjust the calibration factor if required.

For artificial UV:

- Select your lamp type.
- Enter the distance between the lamp and the printing surface.
- Select your calibration factor.

3. Calculate your exposure

The calculator provides an estimated exposure duration based on the supplied conditions.

4. Run a test strip

Use the integrated test-strip helper to experiment with different exposure durations.

Compare the resulting prints after washing and drying, and identify the exposure that produces the desired tonal range.

5. Calibrate your results

Adjust the calibration factor to better match your particular chemistry, paper, coating technique and light source.

Save successful settings as calibration profiles for future use.

6. Start the exposure timer

Use the built-in timer to monitor the exposure period. An optional audible notification indicates when the timer reaches completion.

Calculation Methodology

Sunlight calculations

The sunlight calculator uses a UV Index reference table to establish a baseline exposure time.

The estimated exposure is then adjusted using the selected cloud-cover and calibration factors.

Calculation:

"Estimated exposure = Baseline time × Cloud factor × Calibration factor"

Artificial UV calculations

The artificial UV calculator uses reference exposure times for supported lamp types and adjusts the result according to lamp distance and the selected calibration factor.

Calculation:

"Estimated exposure = Reference time × Distance factor × Calibration factor"

The distance factor uses an inverse-square approximation:

"Distance factor = (Actual distance ÷ Reference distance)²"

These calculations provide starting estimates rather than guaranteed exposure times. Actual results depend on the characteristics of the light source, printing materials and working conditions.

Installation and Access

The application is designed to run directly in a modern web browser.

No installation or additional software is required.

To use the application locally:

1. Clone or download this repository.
2. Open the project folder.
3. Open "index.html" in a modern web browser.
4. Start calculating exposure times.

The application is also suitable for deployment through static web hosting services such as Netlify or GitHub Pages.

Technology

- HTML5
- CSS3
- JavaScript
- Browser Local Storage
- Web Audio API

The application is self-contained in a single HTML file, with no external backend or database required.

Data Storage and Privacy

Calibration profiles, measurement preferences and sound settings are stored locally using browser Local Storage.

No user account or server-side database is required.

Saved profiles are associated with the browser and device being used. Clearing browser storage may remove these settings.

Important Notes

Exposure times are estimates intended to assist with practical cyanotype experimentation.

There is no universal exposure time that works for every cyanotype process.

Actual results can vary according to:

- UV intensity and spectral output.
- Cloud cover and atmospheric conditions.
- Time of day and season.
- Lamp characteristics and age.
- Distance between the light source and printing surface.
- Sensitiser formulation and freshness.
- Paper or substrate characteristics.
- Coating thickness and drying conditions.
- Negative density and transparency.

The inverse-square calculation is an approximation and may not accurately represent every lamp configuration, particularly large or extended light sources.

Always conduct test exposures before committing valuable materials to a full print. Use appropriate precautions when working with UV light sources, including avoiding direct exposure of eyes and skin.

Project

Developer: jaysecotools

Repository: https://github.com/jaysecotools/Cyanotype-exposure-calculator

Licence

Refer to the repository for licensing information.
