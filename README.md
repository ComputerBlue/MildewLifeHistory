# MildewLifeHistory
These files contain the datasets used for the analyses presented in manuscript: 
Variation and correlations between sexual, asexual and natural enemy resistance life-history traits in a natural plant pathogen population


1.  SingleInfectionInoculations.Rdata corresponds to the data used for characterization of the different life-history traits, apart from the ones including the hyperparasite.

Each row corresponds to a distinct inoculation that was monitored every day through the follow-up, and the data contains information on the following aspects: 


"GermiEventType"        0/1 indicator indicating whether the event of germination occurred during the follow-up
"SporuEventType"        0/1 indicator indicating whether the event of sporulation occurred during the follow-up
"ChasmoEventType"       0/1 indicator indicating whether the event of chasmothecia occurrence occurred during the follow-up
"MatureEventType"       0/1 indicator indicating whether the event of mature chasmothecia occurrence occurred during the follow-up
"X1st.time.Germi."      The timing of observing (days post incoculation) first germination event at the inoculation at question
"X1st.time.Sporu."      The timing of observing (days post incoculation) first sporulation event at the inoculation at question
"X1st.time.Chasmo."     The timing of observing (days post incoculation) first chasmothecia event at the inoculation at question
"X1st.time.Matur."      The timing of observing (days post incoculation) first mature chasmothecia event at the inoculation at question
"Nb.Chas..Mature"       The number of mature chasmothecia observed by the end of the follow-up
"plant_genotype"        The genotype of the plant used in the inoculation
"experiment"            The experiment block id
"Nb.Chas..Ima."         The number of immature chasmothecia observed by the end of the follow-up
"X15"                   The infection status (ie. Bevan scale) at day 15
"strain1"               The powdery mildew strain that was inoculated    
"Sporu2Chasmo"          The time from sporulation to chasmothecia
"Germi2Sporu"           The time from germination to sporulation
"Germi2Chasmo"          The time from germination to chasmothecia




2.  InoculationsWithAmpelomyces.Rdata  corresponds to the data from the incoluations conducted jointly with the hyperparasite


Each row corresponds to a distinct inoculation with the Ampelomyces inoculation, that was monitored every day through the follow-up, and the data contains information on the following aspects: 

 "Strain"               The powdery mildew strain in the inoculation
 "X15"                  The infection status (ie. Bevan scale) of the powdery mildew at day 15
 "Nb_immat_chasmo"      The number of immature chasmothecia observed by the end of the follow-up
 "Nb_mat_chasmo"        The number of mature chasmothecia observed by the end of the follow-up
 "X1st_time_germi"      The timing of observing (days post incoculation) first germination event at the inoculation at question
 "X1st_time_sporu"      The timing of observing (days post incoculation) first sporulation event at the inoculation at question
 "X1st_time_chasmo"     The timing of observing (days post incoculation) first chasmothecia event at the inoculation at question
 "X1st_time_matur"      The timing of observing (days post incoculation) first mature chasmothecia at the inoculation at question
 "A1"                   The timing of observing (days post incoculation) first time ampelomyces infection is at stage A1 at the inoculation at question 
 "A2"                   The timing of observing (days post incoculation) first time ampelomyces infection is at stage A2 at the inoculation at question
 "A3"                   The timing of observing (days post incoculation) first time ampelomyces infection is at stage A3 at the inoculation at question
 "A1E"                  0/1 indicator indicating whether the event of A1 occurred in the Ampelomyces infection during the follow-up          
 "A2E"                  0/1 indicator indicating whether the event of A2 occurred in the Ampelomyces infection during the follow-up 
 "A3E"                  0/1 indicator indicating whether the event of A3 occurred in the Ampelomyces infection during the follow-up 
 "GermiE"               0/1 indicator indicating whether the event of germination occurred during the follow-up 
 "SporuE"               0/1 indicator indicating whether the event of sporulation occurred  during the follow-up 
 "ChasmoE"              0/1 indicator indicating whether the event of chasmothecia occurred  during the follow-up 
 "maturE"               0/1 indicator indicating whether the event of mature chasmothecia occurred during the follow-up 
 "Sporu2ampelo1"        Time from sporulation to A1
 "Germi2ampelo1"        Time from sporulatio to A1
 "Sporu2ampelo2"        Time from sporulation to A2  
 "Germi2ampelo2"        Time from sporulation to A2
 "germi2sporu"          Time from germination to sporulation
 "sporu2chasmo"         Time from sporulation to chasmothecia
 "chasmo2matur"         Time from chasmothecia to mature chasmothecia
 "Sporu2ampelo3"        Time from sporulation to A3
 "A28"  
