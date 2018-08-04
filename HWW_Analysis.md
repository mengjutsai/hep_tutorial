HWW Analysis
=============

Outlines
-------------

* Introduction to HWW group and analysis framework
  * Weekly meeting & workshops & analysis paper/notes
  * Twiki and tutorial pages for HWW PxAOD and analysis framework 
  * Details and instructions about CAF and PxAOD
  * From TQSampleFolder to beautiful plots with Python & ROOT
  * Plotting tool working with QFramework or nTuple/TTree
  * Efficiently generate slides containing large amount of plots with Python and Latex
  * Tutorial to EventDisplay & BDT & Fitting
  * Analysis details of HWW 
  
    * What is an event/data/mc/signal/background/weight/ScaleFactor/filter/phase space/
    * The main bkg for our analysis
    * Introduction to basic objects (lep/jet/MET)
    * What is SR/CR, samples we used, the issues we faced
    * What’s the limit for our analysis now
    * What’s normalization factor/nominal/systematics/
    * What we could contribute in the analysis team
    
    
Introduction to HWW group
--------------------------

#### Meetings and Workshops

* Weekly meeting for Higgs to WW group
  * [HWW weekly meeting (Tuesday)](https://indico.cern.ch/category/6420/)
     * General meeting for different topics of HWW contributions covering GGF, VBF and High mass
  * [R21 migration meeting (Thursday, only some periods)](https://indico.cern.ch/category/8790/)
     * Mainly focus on R21 migration since the updates of Athena from R20.7 to R21
     * The rest of meeting in this pages are also covering production code and CAF development
  
* Workshops for Higgs to WW group
  * [HWW workshop (2018)](https://indico.cern.ch/event/714538/page/13514-transportation)
     * Several possible improvement are shown we could try in the legacy paper
     * Ya-Feng gave a talk about [status and outlooks about MC samples](https://indico.cern.ch/event/714538/contributions/3025305/attachments/1659488/2658058/MC_gen_stat_HWWworkshop_v6.pdf)
     * Meng-Ju gave talks about [first R21 MC-MC comparison](https://indico.cern.ch/event/714538/contributions/3024351/attachments/1659750/2658547/HWW_workshop_R21_MC_20180531.pdf) and [limitation & possible improvement for VBF in legacy paper](https://indico.cern.ch/event/714538/contributions/3020450/attachments/1660371/2659743/VBF_HWWworkshop_20180601.pdf)
  * [HWW workshop (2016)](https://indico.cern.ch/event/587413/timetable/?view=standard)
  * [HWW Run2 preparation workshop (2015)](https://indico.cern.ch/event/383521/timetable/?view=standard)
  
#### Production and Analysis Frameworks

* [HWW Derivation framework (DxAOD->PxAOD)](https://gitlab.cern.ch/atlas-physics/higgs/hww/HWWPhysicsxAODMaker)
   * [Grid submission for R21 PxAOD derivation](https://gitlab.cern.ch/atlas-physics/higgs/hww/HWWPhysicsxAODMaker/snippets/522)
   * [Twiki for R20.7](https://twiki.cern.ch/twiki/bin/viewauth/AtlasProtected/HWWxAODCode)
* [New HWW analysis framework @ git](https://gitlab.cern.ch/atlas-physics/higgs/hww/HWWAnalysisCode)
   * [ATLAS CAF Tutorial](https://atlas-caf-tutorial.web.cern.ch/)
   * [ATLAS CAF Tutorial Workshop](https://indico.cern.ch/event/719951/timetable/?view=standard)
* [Old HWW analysis framework @ svn](https://svnweb.cern.ch/trac/atlasoff/browser/PhysicsAnalysis/HiggsPhys/HSG3/HSG3AnalysisCode/HWWlvlv2015/trunk/share?order=name)
   * [Introduction to old CAF](http://atlas-caf.web.cern.ch/)
   * [Twiki for old CAF](https://twiki.cern.ch/twiki/bin/view/AtlasProtected/HWWAnalysisCode)
 
