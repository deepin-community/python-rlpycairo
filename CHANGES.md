CHANGES
=======

This is a summary of changes made to the rlPyCairo source code for each release.
Please refer to mercurial backlogs (using the release dates) for more details.

Full code is available using mercurial see https://hg.reportlab.com/hg-public/rlPyCairo,

The contributors lists are in no order and apologies to those accidentally not
mentioned. If we missed you, please let us know!

CHANGES  0.3.0	 02/06/2023
---------------------------
	* possible pixBuf fixes for bigendian (untested)

CHANGES  0.2.0	 15/12/2022
---------------------------
	* allow usage of \_rl\_renderPM / \_renderPM in \_text2PathDescription
    * switch to pyproject.toml based packaging

CHANGES  0.1.0	 17/10/2022
---------------------------
	* added pil2pict functionality
	* allow import & use of FTTextPath if available

CHANGES  0.0.8	 02/09/2022
---------------------------
	* fix ctm handling
	* make GState fill_rule_values a tuple

CHANGES  0.0.7	 05/03/2021
---------------------------
	* ensure compatibility with pycairo and cairocffi
	* fix up the MANIFEST properly
	* fixes to README etc

CHANGES  0.0.3	 24/02/2021
---------------------------
	* minor fixes to dash array and the slow path based drawString

CHANGES  0.0.2	 22/02/2021
---------------------------
	* handle shapes.Image

CHANGES  0.0.1	 22/02/2021
---------------------------
	* initial working version after using ctx for context rather than canv
	* TODO: handle shapes.Image

CONTRIBUTORS
------------
Claude Paroz: contribution of example which force the attempt to co-opt PyCairo
