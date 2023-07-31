Column (1): Alias

Column (2): Gaia DR3 source id

Column (3): Gaia DR2 source id

Column (4): Adopted mean Spectral type

Column (5): Spectral type(s)

Column (6): Spectral type references (format is only the last name of first author and year)

Columns (7)-(8): Either the same as reference if the spectral type was derived in that reference or the source cited for the spectral type given in the reference and associated number used in tables 

Columns (9)-(10): Effective temperature and associated errors based on spectral types [K]

Columns (11) - (23): Values taken from 2MASS detailed column descriptions can be found at the link: [CalTech user guide](https://www.ipac.caltech.edu/2mass/releases/allsky/doc/sec2_2a.html)
  -  2mass_id: id from 2MASS
  -  2mass_ra: J2000 right ascension with respect to the ICRS [deg]
  -  2mass_decl: J2000 declination with respect to the ICRS [deg]
  -  j_m: 2MASS J mag [mag]
  -  j_msigcom: Combined, or total photometric uncertainty for the default J-band magnitude [mag] 
  -  h_m: 2MASS H mag [mag] 
  -  h_msigcom: Combined, or total photometric uncertainty for the default J-band magnitude [mag] 
  -  k_m: 2MASS K_s mag [mag] 
  -  k_msigcom: Combined, or total photometric uncertainty for the default J-band magnitude [mag] 
  -  k_snr: K_s-band "scan" signal-to-noise ratio.
  -  acatalog_identifier_optical_source: catalog identifier of an optical source from either the Tycho 2 or USNO-A2.0 catalog ('0' = no optical source, 'T' = Tycho 2 source, 'U' = USNO-A2.9 source)
  -  b_m_opt: Blue magnitude of the associated optical source [mag] 
  -  vr_m_opt: Visual or red magnitude of the associated optical source [mag] 

Columns (24)-(58): Values taken from Gaia DR3 detailed column descriptions can be found at the link: [Gaia DR3 documentation](https://gea.esac.esa.int/archive/documentation/GDR3/Gaia_archive/chap_datamodel/sec_dm_main_source_catalogue/ssec_dm_gaia_source.html)
 - ref_epoch: Reference epoch
 - ra: Right ascension [deg]
 - ra_error: Standard error of right ascension [mas]
 - dec: Declination [deg]
 - dec_error: Standard error of declination [mas]
 - parallax [mas]
 - parallax_error: Standard error of parallax [mas]
 - pm: total proper motion [mas/yr]
 - pmra: Proper motion in right ascension direction [mas/year]
 - pmra_error: Standard error of proper motion in right ascension direction [mas/year]
 - pmdec: Proper motion in declination direction [mas/year]
 - pmdec_error: Standard error of proper motion in declination direction [mas/year]
 - ruwe: renormalised unit weight error
 - phot_g_mean_mag: G-band mean magnitude [mag]
 - phot_bp_mean_mag: Integrated BP mean magnitude [mag]
 - phot_rp_mean_mag: Integrated RP mean magnitude [mag]
 - bp_rp: BP - RP colour [mag]
 - bp_g: BP - G colour [mag]
 - g_rp: G - RP colour [mag]
 - radial_velocity: Radial velocity [km/s]
 - radial_velocity_error: Radial velocity error [km/s]
 - l: Galactic longitude [deg]
 - b: Galactic latitude [deg]
 - ecl_lon: Ecliptic longitude [deg]
 - ecl_lat: Ecliptic latitude [deg]
 - in_qso_candidates: Flag indicating the availability of additional information in the QSO candidates table
 - in_galaxy_candidates: Flag indicating the availability of additional information in the galaxy candidates table
 - non_single_star: Flag indicating the availability of additional information in the various Non-Single Star tables
 - phot_variable_flag: Photometric variability flag (NOT_AVAILABLE = source not processed or exported, CONSTANT = source not identified as variable, VARIABLE = identified and processed as variable)
 - azero_gspphot: Monochromatic extinction A_{0} at 541.4 nm from GSP-Phot Aeneas best library using BP/RP spectra [mag]
 - azero_gspphot_lower: Lower confidence level (16%) of monochromatic extinction A_{0} at 541.4 nm from GSP-Phot Aeneas best library using BP/RP spectra [mag]
 - azero_gspphot_upper: Upper confidence level (84%) of monochromatic extinction A_{0} at 541.4 nm from GSP-Phot Aeneas best library using BP/RP spectra [mag]
 - ag_gspphot: Extinction in G band from GSP-Phot Aeneas best library using BP/RP spectra
 - ag_gspphot_lower: Lower confidence level (16%) of extinction in G band from GSP-Phot Aeneas best library using BP/RP spectra [mag]
 - ag_gspphot_upper: Upper confidence level (84%) of extinction in G band from GSP-Phot Aeneas best library using BP/RP spectra [mag]


Columns (59)-(61): Values related to Gaia EDR3 distance taken from [Bailer-Jones et al. (2021)](https://ui.adsabs.harvard.edu/abs/2021AJ....161..147B)
 - r_med_geo: the median of the geometric distance posterior [pc]
 - r_lo_geo: 16th percentile of the geometric distance posterior [pc]
 - r_hi_geo: 84th percentile of the geometric distance posterior [pc]
 
Columns (62)-(85): Values taken from Gaia DR2 detailed column descriptions can be found at the links: 
[Gaia DR2 documentation](https://gea.esac.esa.int/archive/documentation/GDR2/Gaia_archive/chap_datamodel/sec_dm_main_tables/ssec_dm_gaia_source.html)
and [Gaia DR2 RUWE documentation](https://gea.esac.esa.int/archive/documentation/GDR2/Gaia_archive/chap_datamodel/sec_dm_main_tables/ssec_dm_ruwe.html)
 - ref_epoch_dr2: Reference epoch
 - ra_dr2: Right ascension [deg]
 - ra_error_dr2: Standard error of right ascension [mas]
 - dec_dr2: Declination [deg]
 - dec_error_dr2: Standard error of declination [mas]
 - parallax_dr2: Parallax [mas]
 - parallax_error_dr2: Standard error of parallax [mas]
 - parallax_over_error_dr2: Parallax divided by its standard error
 - pmra_dr2: Proper motion in right ascension direction [mas/yr]
 - pmra_error_dr2: Standard error of proper motion in right ascension direction [mas/yr]
 - pmdec_dr2: Proper motion in declination direction [mas/yr]
 - pmdec_error_dr2: Standard error of proper motion in declination direction [mas/yr]
 - phot_g_mean_mag_dr2: G-band mean magnitude [mag]
 - phot_bp_mean_mag_dr2: Integrated BP mean magnitude [mag]
 - phot_rp_mean_mag_dr2: Integrated RP mean magnitude [mag]
 - bp_rp_dr2: BP - RP colour [mag]
 - bp_g_dr2: BP - G colour [mag]
 - g_rp_dr2: G - RP colour [mag]
 - radial_velocity_dr2: Radial velocity [km/s]
 - radial_velocity_error_dr2: Radial velocity error [km/s]
 - a_g_val_dr2: line-of-sight extinction in the G band [mag]
 - a_g_percentile_lower_dr2: a_g_val lower uncertainty [mag]
 - a_g_percentile_upper_dr2: a_g_val upper uncertainty [mag]
 - ruwe_dr2: renormalised unit weight error

Columns (86)-(89): Values related to Gaia DR2 distance taken from [Bailer-Jones et al. (2018)](http://dx.doi.org/10.3847/1538-3881/aacb21)
 - r_est_dr2: the point distance estimate [pc]
 - r_lo_dr2: the lower bounds of the (approximately) 68% confidence interval [pc]
 - r_hi_dr2: the upper bounds of the (approximately) 68% confidence interval [pc]
 - r_len_dr2: Length scale used in the prior for the distance estimation [pc]

Columns (90)-(91): Extinction in the K band and associated error [mag]

Column (92): Extinction in the H band [mag]

Column (93): Extinction in the J band [mag]

Columns (94)-(95): Bolometric correction for 𝐾𝑠 band and associated error [mag]

Columns (96)-(98): Distance module and associated upper and lower errors [mag]

Column (99): Extinction in the V band [mag]

Columns (100)-(101): Intrinsic 𝐾𝑠 mag and associated error [mag]

Column (102): Intrinsic H mag [mag]

Column (103): Intrinsic J mag [mag]

Columns (104)-(106): Absolute K magnitude and associated upper and lower errors [mag]

Columns (107)-(109): Bolometric magnitude and associated upper and lower errors [mag]

Column (110): Stellar radius in log form 

Column (111): Stellar radius [solar radii]

Column (112): Log of luminosity in terms of solar luminosity

Column (113): Log of effective temperature

Columns (114)-(116): Galactic coordinates x, y,z with the sun at (-8.2,0, 0.1) [kpc]

Columns (117): Log of estimated mass loss rates based on Eq. 6 in the associated [paper](http://arxiv.org/abs/2307.08785)

Columns (118)-(129): Variable values taken from Gaia DR3 detailed column descriptions can be found at the link:
[Gaia DR3 variable documentation](https://gea.esac.esa.int/archive/documentation/GDR3/Gaia_archive/chap_datamodel/sec_dm_variability_tables/)
 - range_mag_bp: Difference between the highest and lowest BP magnitudes [mag]
 - range_mag_rp: Difference between the highest and lowest RP magnitudes [mag]
 - range_mag_g_fov: Difference between the highest and lowest G FoV magnitudes [mag]
 - pf: Period corresponding to the fundamental pulsation mode in the G band time series [day]
 - pf_error: error on pf [day]
 - metallicity: Metallicity of the star from the Fourier parameters of the light curve [dex]
 - metallicity_error: Standard error of Metallicity [dex]
 - frequency: Frequency [/day]
 - frequency_error: Standard error of frequency [/day]
 - amplitude: Amplitude [mag]
 - is_cstar: Flag to mark C-stars (TRUE =identified as a C-star, FALSE = identified as O-rich star, and NULL = cannot identify)
 - best_class_name: Name of the best class

Columns (130)-(140): Non-single star values taken from Gaia DR3 detailed column descriptions can be found at the link: 
[Gaia DR3 non-single star documentation](https://gea.esac.esa.int/archive/documentation/GDR3/Gaia_archive/chap_datamodel/sec_dm_non--single_stars_tables/ssec_dm_nss_two_body_orbit.html)
 - nss_solution_type: contains orbit models for sources compatible with an orbital two-body 
 - solution: astrometric binaries, spectra binaries, eclipsing binaries, and certain combos
 - period: Orbital period [day]
 - period_error: Standard error of orbital period [day]
 - eccentricity: Eccentricity of the orbit
 - eccentricity_error: Standard error of eccentricity
 - center_of_mass_velocity: The radial velocity of the centre of mass for SB1, SB1C, SB2 and SB2C solutions [km/s]
 - center_of_mass_velocity_error: Standard error of the radial velocity of the centre of mass [km/s]
 - flags: Quality flag for the achieved NSS solution
 - mass_ratio: Mass ratio
 - mass_ratio_error: Standard error of mass ratio

Columns (141)-(147): Variable values taken from Gaia DR2 detailed column descriptions can be found at the link: 
[Gaia DR2 variable documentation](https://gea.esac.esa.int/archive/documentation/GDR2/Gaia_archive/chap_datamodel/sec_dm_variability_tables/)
best_class_name_dr2: Name of the best class
pf_dr2: Period corresponding to the fundamental pulsation mode (for multi-mode pulsators) in the G band time series [day]
pf_error_dr2: Error of pf [day]
metallicity_dr2: Metallicity of the star from the Fourier parameters of the light curve [dex]
metallicity_error_dr2: Error on the Metallicity [dex]
frequency_dr2: Frequency [/day]
frequency_error_dr2: Error on the frequency [/day]

Columns (148)-(153): Variable values taken from AAVSO detailed column descriptions can be found at the link: [AAVSO VSX](https://vizier.cds.unistra.fr/viz-bin/VizieR-3?-source=B/vsx&-out.max=50&-out.form=HTML%20Table&-out.add=_r&-out.add=_RAJ,_DEJ&-sort=_r&-oc.form=sexa)
 - AAVSO_Type: AAVSO variable flag
 - AAVSO_max_mag: Magnitude at maximum, or amplitude [mag]
 - AAVSO_passband_max_mag: Passband on max magnitude
 - AAVSO_min_mag: Magnitude at minimum, or amplitude [mag]
 - AAVSO_passband_min_mag: Passband on min magnitude
 - AAVSO_Period: Period [day]

Columns (154)-(159): Variable values taken from ASAS-SN V detailed column descriptions can be found at the link: [ASAS-SN Variable Star Database](http://asas-sn.osu.edu/variables)
 - ASASSN-V: ASAS-SN identifier
 - ASASSN_Vmag: Mean Johnson V-band magnitude [mag]
 - ASASSN_Amp: Amplitude [mag]
 - ASASSN_Period: Period [day]
 - ASASSN_Type: ASAS-SN Variability type
 - ASASSN_Prob: Classification probability [0.19/1]


Columns (160)-(163): Variable flag, details on a star’s variable status, reference, and each reference’s symbol in Table 1 in the appendix of associated [paper](http://arxiv.org/abs/2307.08785)

Columns (164)-(167): Binary flag, details on a star’s binary status, reference, and each reference’s symbol in Table 1 in the appendix of associated [paper](http://arxiv.org/abs/2307.08785)

Columns (168)-(170): Measured magnetic field flag, reference, and each reference’s symbol in Table 1 in the appendix of associated [paper](http://arxiv.org/abs/2307.08785)

Columns (171)-(173): Runaway flag, reference, and each reference’s symbol in Table 1 in the appendix of associated [paper](http://arxiv.org/abs/2307.08785)

Column (174): Cluster or OB association

Column (175): Method for collection (Compilation-based, Gaia-Based, within error bars, or Close star addendum)

Column (176): Simbad Classification

Column (177): Region (A-E)




<!--  
-  j_snr: J-band "scan" signal-to-noise ratio.
-  h_snr: H-band "scan" signal-to-noise ratio.
-  2mass_glon: galactic longitude for entry in 2MASS
-  2mass_glat: galactic latitude for entry in 2MASS

ref_epoch,
ra,
ra_error,
dec,
dec_error,
parallax,
parallax_error,
parallax_over_error,
pmra,
pmra_error,
pmdec,
pmdec_error,
ra_dec_corr,
phot_g_mean_mag,
phot_bp_mean_mag,
phot_rp_mean_mag,
phot_proc_mode,
bp_rp,
bp_g,
g_rp,
radial_velocity,
radial_velocity_error,
l,b,ecl_lon,ecl_lat,
priam_flags,
a_g_val,
a_g_percentile_lower,
a_g_percentile_upper,
source_id,
ruwe,
r_est : geometric distance in parsecs
r_lo,
r_hi,
r_len,
result_flag,
modality_flag,
angular_distance : angular distance from gaia source to 2MASS match

BELOW VALUES WERE CALCULATED 
Teff : effective temperature based on spectral types
Teff_error: error on effective temperatures
External_parallax_error,
relative_error,
r_kpc : r_est in kpc
A_Ks : extinction in the K band
A_Ks_sig : uncertainty of K band extinction
A_H : extinction in the H band
A_J : extinction in the J band
BCKs : bolometric correction
BCKs_sig
DM : distance module calculated
DM_sig+
DM_sig-
A_V : extinction in the V band
Ks_0 : intrinsic Ks mag
Ks_0_sig : error on intrinsic K mag
H_0 : intrinsic H mag
J_0 : intrinsic J mag
MKs : absolute K magnitude
MKs_sig+,
MKs_sig-,
Mbol : bolometric magnitude 
Mbol_sig+ 
Mbol_sig- 
log(R/R.)
R*
log(L/L.) : log luminosity in terms of solar luminosity
log_Teff: log effective temperature 
Ks_0-DM
1/parallax : distance derived from parallax 
Mg: absolute G mag
x_kpc: 
y_kpc,
z_kpc,
Method,
Mbol_min,
Alias : main name use for object defined by Simbad
Simbad Classification,
1/(parallax-parallax_0) -->
