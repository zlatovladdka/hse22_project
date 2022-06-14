# hse22_project

Colab Python: https://colab.research.google.com/drive/1J9Ovn4BfZzKbfXSZeGDEqBSiq2EG8b5v?usp=sharing

Colab R: https://colab.research.google.com/drive/1UuePkMBWzNJMI5RP0VFtv6-dELfauHRB?usp=sharing

## Выбранные организмы

| Название организма | Количество последовательностей | Общая длина |  Количество аннотированных генов  | Процент покрытия | Количество участков с ZH-Score > 500  | Общая длина участков с ZH-Score > 500 |
|:-----:|:-------:|:--------:|:-------:|:-------:|:-------:|:-------:|
| _Gordonia alkanivorans_   | 18114 | 4979656 | 4542 | 91.67 | 57900 | 576018 |
| _Gordonia amarae_    | 18506 | 5291543 | 4644 | 90.24 | 56255 | 567694 |
| _Gordonia bronchialis DSM 43247_    | 19207 | 5290012 | 5002 | 92.50 | 63125 | 628254 |
| _Gordonia insulae_   | 21865 | 5962176 | 5481 | 92.33 | 75253 | 751200 |
| _Gordonia iterans_   | 14473 | 4006485 | 3634 | 90.49 | 59055 | 588378 |


### Гистрограммы ZH-Score

![alk](/img/alk.png)
![ama](/img/ama.png)
![bro](/img/bro.png)
![ins](/img/ins.png)
![ite](/img/ite.png)

### Расположение Z-ДНК
| _Gordonia alkanivorans_ | _Gordonia amarae_ | _Gordonia bronchialis DSM 43247_ |  К_Gordonia insulae_  | _Gordonia iterans_ |
|:-----:|:-------:|:--------:|:-------:|:-------:|
|![alk_g](/img/alk_g.png)|![ama_g](/img/ama_g.png)|![bro_g](/img/bro_g.png)|![ins_g](/img/ins_g.png)|![ite](/img/ite_g.png)|


## Кластеры 

### Всего кластеров: 4651
### Распределение по количеству видов

![clusters](/img/clust.png)

Ни один из кластеров не прошёл отбор на сохранение Z-DNA. 

Проведём выравнивание в первых 5 кластерах.

<details>
<summary><b>Кластер 1</b></summary>
>ACY19362.1_chromosomal_replication_initiator_protein_DnaA_Gordonia_bronchialis_DSM_43247
MTSDRDTFG-----EVWQQVVAELNDDEAARDHEPLTRQQKAWLSLVRPLTLAEGFALLTVPTPLVQEQIERNLRDTIRSALSKHLGQPVDLGVRIATPPAEEPVAEPIPAV----------------------LPADDGLSAALTTGVPTPAPGAPFRGPGPVDPAS--ERPR------PDTGDWTAYFAERPTTAPAVPSAN-LNPKYTFDTFVIGASNRFAHASAVAVSEAPARAYNPLFIWGESGLGKTHLLHAAGHYAQRLFPGMRVKYVSTEEFTNDFINSLRDDRRVAFKRRYRDVDVLLVDDIQFLMGKEGIQEEFFHTFNTLHNASKQIVISSDRPPKQLATLEDRLRTRFEWGLITDVQPPDLETRIAILRKKAQMDNIA-VPDDVLELIASKIERNIRELEGALIRVTAFASLNNAELDKSLADVVLQALLPNSGTLEISAASILAITAEYFDISVEELRGPGKTRSIAQARQISMYLCRELTDLSLPKIGETFDRDHTTVMYAERKIRKEMAERRKVYDHVQELTARIKQRAVR
>AVL99165.1_chromosomal_replication_initiator_protein_DnaA_Gordonia_iterans
MADEHDSFS-----AIWSRVVAELSDA-APPDSPPLSRQQKAWLSLVHPLTITSGFALLTAPTALVQEQIERNLRDTISNALSRHLGEPVEIAVRIAEAP-EEPAPAADPVT------------------------AAPPPQNVERVNTGEHAIPARSEGTR----------------------DWASYFDDKHTATPAADSTTTLHPKYTFDTFVIGTSNRFAHASAVAVAEAPARAYNPLFIWGESGLGKTHLLHAAGHYAQRLFPGMRVKYVSTEEFTNDFINSLRDDRQMAFKSRYREVDMLLVDDIQFLEGKEGIQEEFFHTFNVLHNSNKQIVVSSDRPPSKLATLEDRLRTRFEWGLITDVQPPDLETRIAILRKKAQMDKLDQVPDDVLELIASRIERNIRELEGALIRVTAFASLQNTELDRSLAEVVLKALIPDTGPADISAAGIIAITADYYNISVDDLRGTGRKSPLVTYRQIAMYLCRELTDLSLPQIGEAFNRDHTTVIHANRKISEKIGTSTDIYNDVSQLTERIKKRARS
>AZG47030.1_Chromosomal_replication_initiator_protein_DnaA_Gordonia_insulae
MMSDRDSFG-----EIWQSVVAELNNDAAAHDHEPLTRQQKAWLSLVQPLTLAEGFALLTVPTPLVQEQIERNLRDTIRSVLSRHLGQPVDLGVRISTPVVEDPLPDTTTPV----------------------IDRLDGTRGTSQIDGAVAAVAAPTPSTAPSGFDGRGERATG-----PEPADWSTYFAERPTSGQSPSSAN-LSPKYTFDTFVIGASNRFAHASAVAVAEAPARAYNPLFIWGESGLGKTHLLHAAGHYAQRLFPGMRVKYVSTEEFTNDFINSLRDDRRVAFKRRYRDVDVLLVDDIQFLIGKEGIQEEFFHTFNTLHNASKQIVVSSDRPPKQLATLEDRLRTRFEWGLITDVQPPDLETRIAILRKKAQMDNIA-VPDDVLELIASKIERNIRELEGALIRVTAFASLNNAELDKSLAEVVLQALLPNSGTLEVSAASILAITAEYFDISVEELRGPGKTRSIAQARQISMYLCRELTDLSLPKIGETFDRDHTTVMYAERKIRKEMAERRKVYDHVQELTARIKQRAV-
>AZZ80457.1_chromosomal_replication_initiator_protein_DnaA_Gordonia_alkanivorans
MTSDRDTFG-----EVWQQVVAELNDDEAARDHEPLTRQQKAWLSLVRPLTLTEGFALLTVPTALVQEQIERNLRETIRSVLSRHLNEPVDLGVRIQTPRNDEPMPEPAAPE----------------------PRVVNGAAPVDYSAVPGAAIGAGFPATPGAGPAPGGDTGR------P-SGDWASYFAERPTSTPSPSGAN-LNPKYTFDTFVIGASNRFAHASAVAVSEAPARAYNPLFIWGESGLGKTHLLHAAGHYAQRLFPGMRVKYVSTEEFTNDFINSLRDDRRVAFKRRYRDVDVLLVDDIQFLVGKEGIQEEFFHTFNTLHNASKQIVISSDRPPKQLATLEDRLRTRFEWGLITDVQPPDLETRIAILRKKAQMDNIA-VPDDVLELIASKIERNIRELEGALIRVTAFASLNDAALDKSLADVVLQALLPNSGTLEVSAASILAITAEYFDISVEELRGPGKTRSIAQARQISMYLCRELTDLSLPKIGETFDRDHTTVMYAERKIRKEMAERRKVYDHVQELTARIKQRAVG
>QHN20145.1_chromosomal_replication_initiator_protein_DnaA_Gordonia_amarae
MTSDRDSFSRDSFTEVWQRVVAELNSD-SAIGHDPLTRQQKAWLSLVQPLTLVEGFALLAVPTPLVQEQIERNLRDTITTVLSRHLGHPVDLGVRIAAPTEPAPVSGAAAPETETVVTDSSTGRPGNGDFPGGDFPSQDHTPGNGYRPDTPHYSDAQHYSQEPAHYSADERRPIPRPPGTDSDSDWSSYFTGRNAPQPQPTSAN-LNPKYTFDTFVIGASNRFAHASAVAVAEAPARAYNPLFIWGESGLGKTHLLHAAGHYAQRLFPGMRVKYVSTEEFTNDFINSLRDDRRVQFKDRYRAIDVLLVDDIQFLVGREGIQEEFFHTFNTLHNNSKQIVISSDRPPKQLATLEDRLRTRFEWGLITDVQPPDLETRIAILRKKAQMDTIA-VPDDVLELIASKIERNIRELEGALIRVTAFASLNNTELNKSLAEVVLEALLPNSESLEISAASILAITAEYFDISVDELRGPQKTRSIANARQISMYLCRELTDLSLPKIGETFDRDHTTVMYAEKKIRKQMNENRKVYDHVQELAARIKQRAV-
</details>

<details>
<summary><b>Кластер 2</b></summary>
>ACY19363.1_DNA_polymerase_III_beta_subunit_Gordonia_bronchialis_DSM_43247
MKFRVARDEFADSVAWVARSLPSRPPVPVLGCVVLGA-DDG-----LTISGFDYEVSAQESIAAEIAEPGQVLVSGRLLADITKALPNKPVDVTLDGARVAIACGSAKFSLPTMPVEDYPQLPDVPAISGTIPTQLFAEAISQVAIAAGRDDTLPMLTGVRVEIEGSTVVLAATDRFRLAVRELQWEPTDPDTSGAVLVPAKTLSESAKTAGAEGTGVVSLAFGNGSAIGNDGILGILGETKRTTTRLLDAEFPKFRQLLPASHTAIATIDSAPLIEAIKRVALVAERGAQVRLEFGEGSVLLTAGGDEAGKAEEELPVQFAGEALTIAFNPGYLLDGLSAINADTVDFGFTTPS-----------RPAVLRPSSGEQPAADESGAFAAPESAFTYLLMPVRLPG
>AVL99166.1_DNA_polymerase_III_subunit_beta_Gordonia_iterans
MKFRVVRDEFADAVAWVARSLPSRPPVPVLGCVVLTATEQG-----LQVAGFDYEVSATETISAEVAEGGTVLVSGKLLADITRALPNKPVDVTIDGARVAIACGSSKFSLPTMPVEDYPDLPDVPEETGTVPGGLFAEAVSQVAVAAGRDDTLPMLTGVRVEIDGDRIVLAATDRFRLAVRELDWMPRDSAATGAALVPAKTLSDAAKSAGADHAGSVELAFGSGQAIGADGILGITSGPKKTTTRLLDAEFPKFRQLFPASHTSVAAVESAALIEAIKRVSLVAERGAQIRMDFGHDSVLLTAGGDEAGKAEESLDVQFYGEPILIAFNPTYLLDGLAAIGAPRVQFGFTNPEPDGSGERRAAIRPAVLRPASEDEPAADESGSFLAPQSEFSYLLMPVRLPG
>AZG47031.1_DNA_polymerase_III_subunit_beta_Gordonia_insulae
MKFRVARDEFADSVAWVARSLPARPPVPVLGCVVLTAGDN-----GLEVSGFDYEVSAQETVAAEVADSGKVLVSGRLLADITKALPNKPVDVSLDGTRVAITCGSAKFSLPTMPVEDYPELPKPPTVTGTIPAQIFAEAIGQVAVAAGRDDTLPMLTGVRVEIDGNRVVLAATDRFRLAVRELEWDPTAPDTSGAVLVPAKTLSESARTAGSESTGQISLAFGSGSGIGGEGILGILGETKRTTTRLLDAEFPKFRQLLPASHTAVATIDSAPLIEAIKRVALVAERGAQVRMEFNEGSLLLTAGGDEAGKAEEELPVQFQGEPLTIAFNPGYLQDGLSAIGVPSVDFGFTTPS-----------RPAVLRPSTGEEPVADESGAFVAPDSVFTYLLMPVRLPG
>AZZ80456.1_DNA_polymerase_III_subunit_beta_Gordonia_alkanivorans
MKFRVARDEFADSVAWVARSLPSRPPVPVLGCVVLNVGETG-----LTVSGFDYEVSAQENLGAEVAEPGQVLVSGRLLADITKALPNKPVDVTLDGSRVAITCGSAKFSLPTMPVEDYPQLPDVPAITGTIPSQLFAEAISQVAVAAGKDDTLPMLTGVRVEIEGNSVVLAATDRFRLAVRELQWEPSDPDTKGAVLVPAKTLSESAKTAGAEGTGVVSLAFGSGAAIGSDGILGILGETKKTTTRLLDAEFPKFRQLLPASHTAVATIDSAPLIEAIRRVALVAERGAQVRMEFTEGSVLLTAGGDEAGKAEEELPVSFHGEPLTIAFNPGYLQDGLSAINADSVDFGFTTPS-----------RPAVLRPASGEDPVADESGAYVAPESAFSYLLMPVRLPG
>QHN20146.1_DNA_polymerase_III_subunit_beta_Gordonia_amarae
MKFRVARDEFAESVTWVARSLPSRPPVPVLGCVVLTAGDTEPGRDGLTVSGFDYEVSAEETISAEVAEPGRVLVSGRLLADITKALPHKPVDVSLDGSRVAISCGSAKFSLPTMPVEDYPEMPKVPDVTGSLPAGIFAEAITQVAVAAGRDDTLPMLTGVRLEIEGNTVVLAATDRFRLAVRELEWQPTTAEVSGAVLVPAKTLSDSAKTAGSE--GNVELAFGSGGNVGSEGILGILGQNKRTTTRLLDAEFPKFRQLLPASHTAIATIEAAPLIEAIKRVALVAERGAQVRLEFGAGSVLLTAGGDEAGKAEESLEVNFHGEPLTIAFNPGYLLDGLSAMGASSVDFGFTTPS-----------RPAVLRPSSGEEPVADESGAFVAPDSVFTYLLMPVRLPG


</details>


<details>
<summary><b>Кластер 3</b></summary>
>ACY19364.1_DNA_replication_and_repair_protein_RecF_Gordonia_bronchialis_DSM_43247
MFVRELHLRDFRSWRTADLELAAEPTVFTGRNGFGKTNILEALQYLATLRSHRVSTDAPLVHSGATSALVTATVENSGRELTAQLRINAEGANKASINNGPPRRAREVIGILRTVLFAPEDLSLVRGDPTDRRRFIDELVAQRGPLHVAARSDYDRVLRQRAALLKTAGAAMRRGGGDAASVISTLDVWDAQLAEHGAAVTAARVDVLNELRPHVTEAYASIAPHSRPTDLAYLPAAGPDVLPPAGARADVAAIGETLLAQLAQVRTKEIERGVCLVGPHRDDVGIILGDDIAKGFASHGESWSLALALRLGSVALTRAEGVEPVIMLDDVFAELDATRRRKLATFTSDAEQLLVTAAVAEDIPDEIGGRRIGVEVLDDADGRRSVLTPAAADTEGT----------------------------
>AVL99168.1_DNA_replication/repair_protein_RecF_Gordonia_iterans
MFVRALALSDYRSWDRMEIDLRPEPTIFVGRNGFGKTNLLESLFYLATLRSHRVSADAPLVRTGAGAATVRSTVENDGRELTVELTIAAQGSNKATVNTAPVRRPREILGILRAVLFAPEDLALVRGDPAERRRFLDEIVVQLRPIAAGSRADYDRVLRQRSALLKTAGAAMRRSSSEADSVMSTLDVWDEQLAQFGAEVTADRLAVIRELNPLVTQAYSSIAPHSRPARISYRAAAGPEVDASWGGPAAVDEIREVLAARLREVRSKEIDRGLCLIGPHRDDLLLSLGDEPAKGFASHGESWSMALSLRLACVDLLRADGVEPVIMLDDVFAELDAARREKLAAYTGSAEQLLITAAVGEDIPGVLAGRRVSVGVDQEDGRRRSQIIGDEPIGSEGSGPTDDNR--------------------
>AZG47033.1_DNA_replication_and_repair_protein_RecF_Gordonia_insulae
MFVRELRLRDFRSWRDIDLTLRPEPTIFVGRNGFGKTNLLEAVYYLANLRSHRVSSDGPLVRSGSSAATVLGTVENTGRELTVQVQINAEGANKATVNGSPSRRARDVLGILRAVMFAPEDLLLVRGDPSDRRRFVDELVAQRGPRWAAARSDYDRVLRQRSALLKTAGAALRRGGSDADSVISTLDVWDGQLADLGGQVTAARIDVLRDLAPHVTASYASIAPHSRPATLAYRAAAGPEVTSPAEGTASAAGIAEILLARLGELRSKEIDRGVSLVGPHRDDIDIVLGDDVAKGFASHGESWSLALALRLGSVELVRAEGVEPVIMLDDVFAELDVQRRAQLVAFTESAEQLLITAAVPDDIPTSIAGRRVSVGVVEDNGGRHSVVLDDVQASEATGNVSASEATGSVSASEATGQTTAGEGTG
>AZZ80455.1_DNA_replication/repair_protein_RecF_Gordonia_alkanivorans
MFVRELHLRDFRSWQAVDLDLRPGPTVFTGRNGFGKTNLLEALFYLATLRSHRVSSDAPLVHSGSASALVTATVENEGRELTAELRINAEGANKASINRSPARRSRDLLGILRTVLFAPEDLSLVRGDPGDRRRFIDELVAQRGPRWVAARADYDRVLRQRSALLKTAAAALRRGGDQAESVISTLDVWDGQLADLGGQVTAARLQVLAELEPHFTRSYASIAPHSRPATLRYRPAGGVEVET-----ATAESISEILAARLSDLRDKEIDRGMCLVGPHRDDIDIVLGTDVAKGFASHGESWSLALALRLGSVELTRAEGIEPVIMLDDVFAELDAKRREKLVEFTAGAEQLLITAAVADDIPGEIGGRRILVDVVEDADGRRSTVVGDESDSPPE---RVGEPVSGVSDE-------------
>QHN20147.1_DNA_replication/repair_protein_RecF_Gordonia_amarae
MYVRHLSVRDFRSWRSLELDLQPETTIFVGRNGFGKTNILEALYYLTNLRSHRVSTDAPLVQHGAASAVIAATVEHNGRELTAELTVNAAGANKARINGSPARRPRELIGILRSVMFAPEDLLLVRGDPADRRRFVDELVAGQGPRWVAARADYDKVLRQRTALLKTAGAAMRRGGGEAASVISTLDVWDGQLADLGAQITAARIDVLAALRPHVVTAYASIAPHSRPADLRYRPAAGPHLLPGPGESAAPEEIRAHLLAGLAELRNKEIERGVCLVGPHRDDVDVVLGDQVAKGFASHGESWSLALSLRLGSVELLRADGIEPVIMLDDVFAELDAARRRQLVEFTASAQQLLITAAVAEDIPDGLGGRTLDIDTVTDDTGRYSRITTLQP---------------------------------


</details>


<details>
<summary><b>Кластер 4</b></summary>
>ACY19365.1_protein_of_unknown_function_DUF721_Gordonia_bronchialis_DSM_43247
MS-------TDPTGTPG----TPDELGGYERARRALEEARAAARAAGKSVGHGRASPVRRPASGN-KKRRRWSGAGPDSRDPQPLGRLAGGVARERGWQAKIGEGTLFGMWDQIVGADIAAHAQPISLRDKVLHVQAESTAWATQLRYVQAQIIAKIAAALGDGMVTSLRITGPKGPSWRKGERHVRGRGPRDTYG
>AVL99169.1_hypothetical_protein_C6V83_01520_Gordonia_iterans
MN-------DDAGHSPG-----------YDVARRALEEARAQAQAAGKQVGRGRSGPVASPRRTGDRRRRTWSGAGPDGRDPQPFGRLVGSLARTRGWSPKISEGAVFGSWPAIVGPEIAAHAEPSALNDGVLHVRAESTAWATQLRYMQPQILAKIAAAVGDGVVKSLRITGPSAPSWRKGPLHVSGRGPRDTYG
>AZG47034.1_hypothetical_protein_D7316_03639_Gordonia_insulae
---------MSETGSPGGG---TSEPTGYERARQALEEARAAARAAGKSVGQGRSSPAARSRRTA-GRRRTWSGSGPDARDPQPLGRLAGHIAKERGWQPHIGQGTLFGMWDQIVGVDIAAHAQPTALSDNVLHIQAESTAWATQLRYMQGTILAKIAGAVGDGMVTTLRITGPKAPSWRKGPRHISGRGPRDTYG
>AZZ80454.1_DUF721_domain-containing_protein_Gordonia_alkanivorans
MSDEAPSSRPDAAGEPSNRPIEPGELGGYERARKALEEARAAARAAGKSVGRGRASPVRRTPRGA-QTRKRWSGSGPDARDPQPFGRLVGGLAKDRGWQEKIGEGTLFGMWDQIVGADIAAHAKPIELRDNVLHVQAESTAWATQLRYVQSQILAKIAAAVGDGVVKSLRISGPKGPSWRKGERHVRGRGPRDTYG
>QHN20148.1_DUF721_family_protein_Gordonia_amarae
MADD-----TSAHTPPNGG--IPKDRGGYELASKALEEARAAARAAGKSVGQGRASPVRR-RRTT-GTRRSWSGAGPDARDPQPFGRLAAQIAGSRGWQADLGKGMVFGMWDTIVGPDIAAHAQPTLLRDKVLHVQAESTAWATQLRYIQSQVLAKIAEGVGHGVVTSLRITGPKAPSWKKGPRSVPGRGPRDTYG


</details>


<details>
<summary><b>Кластер 5</b></summary>
>ACY19366.1_DNA_gyrase_B_subunit_Gordonia_bronchialis_DSM_43247
MADSKDTAGS------KSKSKKSGEYSADSISILEGLEAVRKRPGMYIGSTGERGLHHLIWEVVDNSVDEAMAGYASKVEVTLLEDGGVEVVDDGRGIPTDMHATGSPTVEVVMTQLHAGGKFDSDAYAVSGGLHGVGISVVNALSTKVELEINYGGFHWEQTYDHAKPQPLEKGDATRKTGTLVRFWPDPEIF-ETTVFSAETVARRLQEMAFLNKGLTITLTDKRP---RAVEAPPGDANGDESVA---DAAETVKTEEEK-KADAKPKTRTYHYPDGLVDYIKHLN-RTKQPIHNSVIGFTAKGTGHEVEIAMQWNAGYSESVHTFANTINTHEGGTHEEGFRAALTSTVNKYALDKKLLKEKDGKLTGDDIREGLAAVISVKVGDPQFEGQTKTKLGNTEVKGFVQKTCNEHLAHWFESNPAEAKIIIKKAVDSSQARLAARKARELVRRKTATDIGGLPGKLADCRSNDPSKCEVYIVEGDSAGGSAKSGRDSMYQAILPLRGKIINVEKARIDRVLKNAEVQSIITAFGTGIHDEFDIAKLRYHKIVLMADADVDGQHISTLLLTLLFRFMRPLIEHGHVYLAQPPLYKLKWQ--KREPEFAYSDRERDGLLEAGRTAGWKINTDDGIQRYKGLGEMNAKELWETTMDPEVRVLRQVTLDDAAAADELFSILMGEDVAARRSFIARNAKDVRFLDV
>AVL99170.1_DNA_topoisomerase_(ATP-hydrolyzing)_subunit_B_Gordonia_iterans
MADTSSSESK------KPKKSTSGEYGADSISILEGLEAVRKRPGMYIGSTGERGLHHLIWEVVDNSVDEAMAGHATRVDVTILADGGVQVVDDGRGMPVGMHASGVPAVEVIMTQLHAGGKFDSDSYAVSGGLHGVGISVVNALSTKVELEIQRDGHVWTQAYDYAKPNTLTTIGDSTTTGTTVRFWPDGKIF-ETTTFNAETIARRLQEMAFLNKGLTITLTDERLTENEAEAEVEGEG-GD----------ASLKSEEEKASELAKVRSRVYHYPEGLVDFVRHLN-RTKHPIHNTVIDFAAKGEGHEVEIAMQWNNGYSESVHTFANTINTHEGGTHEEGFRAALTSTVNKYALDKKLIKEKDGKLTGDDIREGLAAVISVKVADPQFEGQTKTKLGNTEVKGFVQRTCNEHLGHWFEANPAEAKIIVRKAADSAQARMAARRARELVRRKTATDIGGLPGKLADCRSNDPAKCEVYIVEGDSAGGSAKSGRDSMYQAILPIRGKIINVEKARIDRVLKNAEVQSIITAFGTGIHDEFDLAKLRYHKIVLMADADVDGQHIATLLLTLLFRFMRPLIEHGHVYLAQPPLYKLKWQK-GAEPEYAYSDRERDAMLEAGLAAGKKINKDDGIQRYKGLGEMNASELWETTMNPETRILKKVTLDDAAAADELFSILMGEDVAARRGFIARNAKDVRFLDV
>AZG47035.1_DNA_gyrase_subunit_B_Gordonia_insulae
MADTNDTPGSDSAAEKKRKTKKPDEYGAESISILEGLEAVRKRPGMYIGSTGERGLHHLIWEVVDNSVDEAMAGYASRVDVSLLEDGGVQVVDDGRGIPVSMHATGVPTVEVVMTQLHAGGKFDSDSYAVSGGLHGVGISVVNALSTKVELEIQRDGHKWSQTYDYAKPGTLEKGDATRKTGTTTRFWPDPAIF-ETTTFSAETVARRLQEMAFLNKGLTITLTDNRLSDEAAVAEAEMDGSGDDTAP------EMIKSDAEKARKAAKVRTRTYHYPDGLVDYIKHLN-RTKNPIHTSVVGFTAKGTGHEVEIAMQWNAGYSESVHTFANTINTHEGGTHEEGFRAALTSTVNKYAVDKKLLKEKDGKLTGDDIREGLAAVISVKVGDPQFEGQTKTKLGNTEVKSFVQKTCNEHLGHWFEANPAEAKIIIKKAVDSAQARMAARKARELVRRKTATDIGGLPGKLADCRSNDPSKCEVYIVEGDSAGGSAKSGRDSMYQAILPLRGKIINVEKARIDRVLKNTEVQSIITAFGTGIHDEFDIAKLRYHKIVLMADADVDGQHISTLLLTLLFRFMRPLIEHGHVFLAQPPLYKLKWQ--KSEPEFAYSDRERDGLLEAGRAAGRKINADDGIQRYKGLGEMNAKELWETTMDPAVRVLRQVTLDDAAAADELFSILMGEDVAARRSFIARNAKDVRFLDV
>AZZ80453.1_DNA_topoisomerase_(ATP-hydrolyzing)_subunit_B_Gordonia_alkanivorans
MADTNDTGP-------KKSKKKPSEYGADSINILEGLEAVRKRPGMYIGSTGERGLHHLIWEVVDNSVDEAMAGFASRVDVTLLEDGGVQVVDDGRGIPVEKHRTGVPTVEVVMTQLHAGGKFDSDSYAVSGGLHGVGISVVNALSTKVELEIARDGHNWTQTYSYAKPGALEQGDATRKTGTTVRFWPDPDIFTETTRFNAETVARRLQEMAFLNKGLTITLTDQRP---QAVEPP-GDPNGDEDAP-TTDVAEVVLSETEKAQAAAKPKTRTYHYPDGLVDYIKHLN-RTKQSIHNTVIGFSAKGEGHEVEIAMQWNAGYSESVHTFANTINTHEGGTHEEGFRAALTSTVNKYALEKKLIKEKDGKLTGDDIREGLAAVISAKVSDPQFEGQTKTKLGNTEIKGFVQRTCNEHLGHWFEANPAEAKIIIKKAADSAQARMAARRAREMVRRKTATDIGGLPGKLADCRSNDPTKCEVYIVEGDSAGGSAKSGRDSMYQAILPLRGKIINVEKARIDRVLKNAEVQSIITAFGTGIHDEFDIAKLRYHKIVLMADADVDGQHISTLLLTLLFRFMRPLIEHGHVFLAQPPLYKLKWQ--KSAPEFAYSDRERDGLLEAGRAAGKKINTDDGIQRYKGLGEMNAKELWETTMDPAVRVLRQVTLDDAAAADELFSILMGEDVAARRSFIARNAKDVRFLDV
>QHN20149.1_DNA_topoisomerase_(ATP-hydrolyzing)_subunit_B_Gordonia_amarae
MAETNDASSNN-----RKPNKKPGEYGADSINILEGLEAVRKRPGMYIGSTGERGLHHLIWEVVDNSVDEAMAGYASRVDVTLLADGGVEVIDDGRGIPVATHATGVPTVEVVMTQLHAGGKFDSDSYAVSGGLHGVGISVVNALSTKVELEIKRDGFQWSQTYLNSEPQTLHQGAASRKTGTTTRFWPDPAIFTETTRFNAETVARRLQEMAFLNKGLTITLTDNRP---QAVEAP-GDPNGDGDTPGGTELAEVVQSPAQK--ATAKSKTRTYHYADGLIDYIKHINKRSKNPIHQSVIGFSGKGTGHEVEIAMQWNDGYSESIHTFANTINTHEGGTHEEGFRAALTSTVNKYAADKKLIKEKDTKLTGDDIREGLAAVISVKVSDPQFEGQTKTKLGNTEVKGFVQKICNEHLAHWFESNPAEAKNIIKKAVDSAQARAAARRARDMVRRKTATDIGGLPGKLADCRSNDPALCEVYIVEGDSAGGSAKSGRDSMYQAILPIRGKIINVEKARIDRVLKNTEVQSIITAFGTGIHDEFDIAKLRYHKIVLMADADVDGQHISTLLLTLLFRFMRPLIEHGHVYLAQPPLYKLKWQGKNAEPEFAYSDRERDGLLEAGRAAGKKINSDDGIQRYKGLGEMNAKELWETTMDPAVRVLRQVTLDDAAAADELFSILMGEDVAARRSFIARNAKDVRFLDV


</details>
  
  



## Бонус

Файлы, сгенерированные в R, лежат в папке data. 
