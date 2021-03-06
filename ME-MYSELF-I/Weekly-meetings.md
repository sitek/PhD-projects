# Weekly Meetings

* [22 September 2017](#date-22-september-2017)
* [29 September 2017](#date-29-september-2017)
* [27 October 2017](#date-27-october-2017)
* [05 January 2018](#date-05-january-2018)

### Date: 05 January 2018

#### Who did you help this week?
Helped Nick create 3D surface images for his CMRO2 paper.

#### Who helped you this week?
* Mathias helped with fmriprep for 7T data
* Jakub helped with X display issues for visualization

#### What did you achieve?
Catching back up after the break - some work from previous month or so:
* processed ex vivo diffusion data in dipy
* ran at multiple resampled resolutions
* currently implementing target-based tractography
* registered downsampled anatomical image to DWI; working on full res
* contacted/confirmed 2 members of DAC

#### What did you struggle with?

* applying hires-DWI transformation (based on downsampled hi res) to full res anat image
* completing fmriprep of 7T data, particularly applying field maps

#### What would you like to work on next week?

* finish target-based tractography in dipy
* anatomical definitions on (transformed) hi res data
* manuscript: methods, background
* submit Harvard travel award final paperwork (due 1/11)

#### Where do you need help from Satra?

* planning/prepping for DAC meeting
* applying downsampled transform to full res anatomical data (if not resolved)

#### Any other topics

---

### Date: 27 October 2017

#### Who did you help this week?

Helped Nick with functional parcellation of CMRO2 data + grabbing atlas labels for each parcel based on CoM.

#### Who helped you this week?

@satra helped define goals and task priorities at our meeting 10/24 & also connected with collaborators for setting up helpful meetings

#### What did you achieve?

* wrote a python/pandas script to grab label names from an atlas (via `whereami`) for functional parcellation
* outlined PhD goals/plan

#### What did you struggle with?

* still having issues registering ex vivo images
* still having issues with tractography outside of DSI Studio for these data

#### What would you like to work on next week?

* SNL poster: decide what changes from SMC poster (add DWI? Greg's acoustics?)
* SNL poster: update resting state images
* SNL poster: update subject lists, analysis
* ex vivo registration
* ex vivo tractography outside DSI Studio

#### Where do you need help from Satra?

* probably ANTs help registering the ex vivo images
* feedback on SNL poster (once new data/figures ready)

#### Any other topics


---

### Date: 29 September 2017

#### Who did you help this week?

#### Who helped you this week?

Satra helped with registering GRE and DWI images in ANTs (still running). Jakub continued helping get DSI Studio to run in a container on openmind to help with memory resources, high resolution images.

#### What did you achieve?

* made presentations summarizing projects

#### What did you struggle with?

* reorienting the GRE image into the orientation of the diffusion image (again)
* dipy on ex vivo data - openmind resources issues, then tracking issues once it ran
* registering subcortical atlas to whole brains for HCP diffusion seeds

#### What would you like to work on next week?

* subnuclei definitions on the GRE image, especially CN
* run dipy reconstruction on the ex vivo data
* run dipy reconstruction on HCP data (with gross spherical seeds to start)
* Harvard Horizons application
* SHBT 25th Anniversary poster
* continue outlining dissertation proposal
* clinical application - determine data, think about preregistration

#### Where do you need help from Satra?

* perhaps dipy with ex vivo, if I still can't figure out what's going wrong
* thoughts on SHBT poster

#### Any other topics

---

### Date: 22 September 2017

#### Who did you help this week?

I talked with Nick about his CMRO2 data and will be helping him analyze those when he's done with processing. This is a reanalysis from a previous version.

#### Who helped you this week?

Jakub helped look for info about reorienting an image and about ITK-SNAP.

#### What did you achieve?

* imported and updated this repository for updates
* learned basics of ITK-SNAP and used it to start segmenting ex vivo GRE data

#### What did you struggle with?

* reorienting the GRE image into the orientation of the diffusion image

#### What would you like to work on next week?

* subnuclei definitions on the GRE image
* run dipy reconstruction on the ex vivo data
* Harvard Horizons application
* continue outlining dissertation proposal
* decide on clinical data for tractography portion (meeting at MEE)

#### Where do you need help from Satra?

* GRE orientation issues (can't overlay/warp to diffusion until rotated)

#### Any other topics

Let me know if you hear back from Jon!

---

## Template (Copy template, add date link on top, and replace text, newest first)

### Date: [INSERT DATE OF MEETING]

#### Who did you help this week?

Replace this text with a one/two sentence description of who you helped this week and how.


#### Who helped you this week?

Replace this text with a one/two sentence description of who helped you this week and how.

#### What did you achieve?

* Replace this text with a bullet point list of what you achieved this week.
* It's ok if your list is only one bullet point long!

#### What did you struggle with?

* Replace this text with a bullet point list of where you struggled this week.
* It's ok if your list is only one bullet point long!

#### What would you like to work on next week?

* Replace this text with a bullet point list of what you would like to work on next week.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Where do you need help from Satra?

* Replace this text with a bullet point list of what you need help from Kirstie on.
* It's ok if your list is only one bullet point long!
* Try to estimate how long each task will take.

#### Any other topics

This space is yours to add to as needed.
