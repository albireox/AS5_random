# AS5_random
Short ideas for the After Sloan 5 Blue Skies process

## Instructions
Fork this repository, add a bullet point to the list of ideas below, and *add your name* to the author list, and generate a pull request.
If you add an idea, you must add your name, and *vice versa*.

## Style notes
Keep it brief, but specific. Boldface a phrase or sentence that serves as the "title" for your idea.

## Authors
- **David W. Hogg** (Flatiron)
- **Andy Casey** (Monash)
- **Ilija Medan** (Vanderbilt Univ.)
- **Zach Way** (Georgia State Univ.)
- *[ADD YOUR NAME HERE]*

## Ideas

- Create a **live auction for spectra**. The interface is: Choose your instrument, your observing conditions, exposure time, time constraints, and so on, and a *maximum amount* you are willing to pay for one spectrum (the bid). At every interval (15 minutes, say), we find the telescope pointing and field configurations that maximize revenue. We charge a discounted rate to the bids, which is discounted because we bill a total amount to all the winning bids that delivers to us a total revenue that is halfway between the best field's total of bids and the second-best field's total of bids (I believe there is research about this structure). *&mdash; Hogg*

- **Follow the *LSST* footprint**, by some sparse sampling. Operate a time-domain survey that is always pointing at a field that was observed by *LSST* within the last *N* minutes. Permits all-sky survey targets and also *LSST*-triggered target-of-opportunity targets in the same program. Could be combined with the live auction idea above. *&mdash; Hogg*

- **Fill out the binary system parameter space**. There will be many binary systems where Gaia DR4 will be unable to solve the complete orbit. Some will be too faint, particularly for stars in the dusty disk. Other systems might be multi-modal: two or more likely regions of binary parameter space. In these situations, a (possibly) well-timed RV precise (~100 m/s) RV measurement from APOGEE will resolve the orbit. *&mdash; Casey*

- **A noisier expansion of Galactic Genesis**. APOGEE is the only current or planned spectrograph that can survey the Galactic plane at scale. GALAH, 4MOST, and WEAVE either avoid the plane entirely, or produce shallow samples. A low S/N spectrum (~20) for millions more Galactic Genesis targets would be sufficient to measure a radial velocity, to measure interstellar dust along the line of sight. *&mdash; Casey*

- **Narrow-band photometry yields abundance indicators for stellar litmus tests.** There are stellar astrophysics questions where competing physical explanations might be differentiated by the measurement of a single absorption line. For example, is this star lithium-rich? Is there also high berylium, or high chromospheric activity in the helium lines? Is the lead abundance in this star very high (indicating one nucleosynthetic process), or very low (indicating the other)? With good models of stellar spectra, an extremely narrow-band photometric filter can be sufficient to perform these litmus tests for large numbers of stars, where high-resolution spectroscopy would otherwise be too expensive. *&mdash; Casey*

- **Bridging the gap between low- and high-resolution spectroscopy for low-luminosity stars.** Low-luminosity stars are ubiquitous across the sky and are observed in large numbers in surveys like Gaia. Notably in Gaia DR3, a large number of these low-luminosity stars have low-resolution Gaia XP spectra. In SDSS though, 99% of APOGEE spectra are of targets with M<sub>G</sub> < 10.5 mag, meaning the vast majority of these low-luminosity objects haven't been systematically targeted in higher resolution spectroscopic surveys. We propose to make these a high priority in a future iteration of SDSS. This would require extending exposure times with APOGEE to achieve sufficient signal-to-noise for these fainter objects. This could open an additional observing mode for the survey. Specifically, APOGEE fibers could be parked on low-luminosity (and other faint) objects for long exposure times, while BOSS fibers are reconfigured at the typical 15 minute exposure time cadence. This would be the first time a large number of these low-luminosity objects are systematically observed with high resolution spectroscopy, which would help with our understanding of low-mass stars in the full range of parameter space. *&mdash; Ilija Medan and Zach Way*
  
