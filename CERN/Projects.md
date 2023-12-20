#CERN 

## Actions:
[Jira](https://its.cern.ch/jira/plugins/servlet/project-config/SEXTWG/summary)
Luke:
[SEXTWG-6](https://its.cern.ch/jira/browse/SEXTWG-6) - Accept the [merge request](https://gitlab.cern.ch/acc-models/acc-models-ea/-/merge_requests/2) (Change the location of TCMAA.X0400001 (correct is between 65 cm and 105 cm)).   
[SEXTWG-12](https://its.cern.ch/jira/browse/SEXTWG-12) - Provide the distribution of the beam after interaction with air in P42 XTAX. 
[SEXTWG-15](https://its.cern.ch/jira/browse/SEXTWG-15) - Accept the [merge request](https://gitlab.cern.ch/acc-models/acc-models-ea/-/merge_requests/3) (Change MDX aperture to 80 mm). 

Me:
- We should check the P4 TAX apertures with Luke to make sure they suit us in the future. They can be optimised because NA-CONS will replace the P4 TAX blocks in Long Shutdown 3 and we will have an opportunity to modify the design. There is an EDMS document 2747997 where we should give input: https://edms.cern.ch/document/2747997/0.1 . Beam transverse profile after T4/T10 targets?
- P42 seq check (apertures, magnet strengths and xyz)
- Check position of dump with SRR and update a sequence together with Luke and BE-EA
- Tunnel slope
- Issue with magnet types
- [SEXTWG-16](https://its.cern.ch/jira/browse/SEXTWG-16) - Verify Luke's changes
- [SEXTWG-10](https://its.cern.ch/jira/browse/SEXTWG-10) - Verify dump position using space reservation request. Ask Luke and Rui about dump position
- [SEXTWG-12](https://its.cern.ch/jira/browse/SEXTWG-12) - Check Rui's comments, take into account finite height of the target.
- [SEXTWG-20](https://its.cern.ch/jira/browse/SEXTWG-20) - Add shared optics. Summarise split ratio studies.

**Tasks**
- P42 line check
- Optics rematching Try to fly around T4 target sheets or hit any chosen sheet Reduce beam size inside the TAX in order to minimise scattering 
- Slow extraction phase space folding technique


## **Resources**
ABT optics and code repository https://gitlab.cern.ch/groups/abt-optics-and-code-repository 
Acc-models https://gitlab.cern.ch/acc-models
 **SHiP**
[17th SHiP Collaboration Meeting](https://indico.cern.ch/event/803758/)
	[HI-ECN3 (M. Fraser)](https://indico.cern.ch/event/1325184/contributions/5606084/attachments/2732274/4750160/MFraser_26thSHIP_collab_HI-ECN3.pdf)


## **ECN3**
**Optics rematching**:
[List of studies for Luke with optimisation examples](https://indico.cern.ch/event/1290323/contributions/5421728/attachments/2660809/4609419/BD_studies.pdf) (M. Fraser)
[T4 kick response and error studies](https://indico.cern.ch/event/1297402/contributions/5461867/attachments/2670226/4628617/t4_bump_MD_2.pdf) (M. Fraser, L. Dyks)
[T4 bump MD studies](https://indico.cern.ch/event/1290323/contributions/5421730/attachments/2660944/4609671/t4_bump_MD.pdf) (M. Fraser)
[Rematched optics example](https://gitlab.cern.ch/abt-optics-and-code-repository/multi-user-tt20/-/blob/master/t4bump_analysis.ipynb?ref_type=heads) (M. Fraser)
[Interaction with splitters](https://gitlab.cern.ch/parrutia/madcoll) (P. Arrutia)

**P42 beam dump:**
[Dump func spec](obsidian://open?vault=Obsidian%20Vault&file=CERN%2FECN3%2FP42%20dump%20func%20spec)
[P42 beam dump](https://indico.cern.ch/event/1223801/contributions/5148553/attachments/2553467/4399479/TT20_MD_quad_scan.pdf) (R. Ramjiawan)
[Absorber specifications](https://indico.cern.ch/event/1252011/contributions/5260240/attachments/2590544/4470268/Ramjiawan_SFTPRO_dump.pdf) (R. Ramjiawan)
P42 space reservation request [SRR_P42_dump.docx](https://cernbox.cern.ch/files/spaces/eos/user/m/mfraser/ECN3%20Task%20Force/SRR_P42_dump.docx) (M. Fraser)
HI-ECN3 WP3 Coordination Meeting materials [P42 beam dump meeting](https://indico.cern.ch/event/1348108/) (R. Ximenes)
<a href="https://cds.cern.ch/record/2848908?ln=en" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;">SPS Operation and Future Proton Sharing Scenarios for the ECN3 facility</a>

**TT20-P42 mad-x sequences check (**[SEXTWG-5](https://its.cern.ch/jira/browse/SEXTWG-5)**):**
TT24-P42 stitched model <a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/tree/main/sps_extraction/tt24p42_unsplit/line" rel="noopener" class="external-link" target="_blank"><u>https://gitlab.cern.ch/acc-models/acc-models-tls/-/tree/main/sps_extraction/tt24p42_unsplit/line</u></a>  <u>(F. Velotti)</u>
<a href="https://gitlab.cern.ch/acc-models/acc-models-ea/-/blob/en-ea-le/P42/STANDARD_P42_YETS%202022-2023.seq?ref_type=heads" rel="noopener" class="external-link" target="_blank"><u>STANDARD_P42_YETS 2022-2023.seq</u></a>		[raw](https://gitlab.cern.ch/acc-models/acc-models-ea/-/raw/en-ea-le/P42/STANDARD_P42_YETS%202022-2023.seq)		no apertures
<a href="https://gitlab.cern.ch/acc-models/acc-models-ea/-/blob/en-ea-le/P42/p42_2023.str?ref_type=heads" rel="noopener" class="external-link" target="_blank"><u>p42_2023.str</u></a>								[raw](https://gitlab.cern.ch/acc-models/acc-models-ea/-/raw/en-ea-le/P42/p42_2023.str)		
<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/blob/main/sps_extraction/tt24t4/tt24t4.seq?ref_type=heads" rel="noopener" class="external-link" target="_blank"><u>tt24t4.seq</u></a>								<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/raw/main/sps_extraction/tt24t4/tt24t4.seq" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;"><u>raw</u></a>
<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/blob/main/sps_extraction/tt24p42_unsplit/line/tt24_unsplit.inp?ref_type=heads" rel="noopener" class="external-link" target="_blank"><u>tt24_unsplit.inp</u></a>							<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/raw/main/sps_extraction/tt24p42_unsplit/line/tt24_unsplit.inp" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;"><u>raw</u></a>		<span style="color:#e4afaff;">initial conditions</span>
<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/blob/main/sps_extraction/tt24p42_unsplit/line/tt24p42.str?ref_type=heads" rel="noopener" class="external-link" target="_blank"><u>tt24p42.str</u></a>								<a href="https://gitlab.cern.ch/acc-models/acc-models-tls/-/raw/main/sps_extraction/tt24p42_unsplit/line/tt24p42.str" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;"><u>raw</u></a>		<span style="color:#e4afaff;">magnet strength</span>


**Tunnel slope**
<a href="https://edms.cern.ch/ui/#!master/navigator/document?P:100463241:1735416355:subDocs" rel="noopener" class="external-link" target="_blank"><u>Layot vide zone North | Document 1079476 (v.1) (cern.ch)</u></a>
Apparently at the start of TT83 we have 2.6% slope that after around 150 m becomes 0.95%.
I hope it can be useful for your simulations. (G. Romagnoli)

**Issue with magnet types**
MDS and MDX magnets apertures are to be checked, especially around the dump. Most likely they are 80 cm quads. Contact ([Philippe Boisseaux-Bourgeois](https://its.cern.ch/jira/secure/ViewProfile.jspa?name=pboissea)
[pboissea](https://its.cern.ch/jira/secure/ViewProfile.jspa?name=pboissea))

**T4 VXSS ?**
VXSS Consolidation Strategy <a href="https://edms.cern.ch/document/2933169" rel="noopener" class="external-link" target="_blank"><u>https://edms.cern.ch/document/2933169</u></a> (T4 will be without VXSS until LS3)

<p style="text-align:justify;margin:0">FEM analysis of the windows of the T4 TBIU/Ds (250μm Titanium foil), wobblers (0.5mm of Al5052-H19) and vacuum chamber upstream the TAX (0.2mm of Al5052-H19) <a href="https://edms.cern.ch/document/2812844" rel="noopener" class="external-link" target="_blank"><u>https://edms.cern.ch/document/2812844</u></a> 
</p>

**TT20 new equipment**
[Fast spill monitors](https://indico.cern.ch/event/1340570/contributions/5643409/attachments/2747326/4781566/20231107_FSM_Status_SPSMPC_SBenitez.pdf) (S. Benítez Berrocal) 
OTR: BTV210272
SERVO SPILL (BSI): BSI 210216
DIAMOND BEAM LOSS MONITOR (DBLM): BLMD.21672, BLMD.210558

**XTAX:**
[TAXs in TCC2 CodiMD](https://codimd.web.cern.ch/qhudHgH6SY67SGjTZ1tzbA)
[Functional specification](https://edms.cern.ch/document/2747997/0.1)
[P42 losses](https://indico.cern.ch/event/1290323/contributions/5421729/attachments/2660740/4609351/lukeDyksp42BDSIM_06062023.pdf) (L. Dyks)


## **Slow extraction**
SLAWG project: https://gitlab.cern.ch/abt-optics-and-code-repository/projects/SLAWG
[Sloex eos directory](https://cernbox.cern.ch/files/spaces/eos/project/s/sloex/afs/cern.ch/project/sloex)
Example talk for phase space folding: https://indico.fnal.gov/event/20260/contributions/56668/
simple example with Xsuite for SPS slow extraction: <a href="https://gitlab.cern.ch/sps-projects/sx_xsuite_sps" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;">https://gitlab.cern.ch/sps-projects/sx_xsuite_sps</a>
PIMMS Study guide to slow extraction: https://inspirehep.net/files/7ae070188baebe539cc4659771f73bad

Linda’s sim output <a href="https://cernbox.cern.ch/files/spaces/eos/user/m/mfraser/Documents/SLAWG%20PRSTAB/PRAB_octupoles/octu_opt_test_slices_SB2e04_MBA163_opknob_highstats_nopc_sextu_2100_octu_-2450_ang_-1200_zs_41600_aper_bump950" rel="noopener" class="external-link" target="_blank"><u>octu_opt_test_slices_SB2e04_MBA163_opknob_highstats_nopc_sextu_2100_octu_-2450_ang_-1200_zs_41600_aper_bump950</u></a> 
Plotting sim output <a href="https://cernbox.cern.ch/files/spaces/eos/user/m/mfraser/Documents/SLAWG%20PRSTAB/plot_octupoles_from_linda.ipynb" rel="noopener" class="external-link" target="_blank" style="color:#e4afaff;"><u>plot_octupoles_from_linda.ipynb</u></a> 

ucap_sx_monitoring: https://gitlab.cern.ch/sps-projects/ucap_sx_monitoring 



## **CHIMERA**
[TFB development features 2024](https://codimd.web.cern.ch/ERX5J2X2TK6n66ySES8bxw?view)