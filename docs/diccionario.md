DICCIONARIO 
LISTA DE VARIABLES 
Índice de Pobreza Global (BMI / World Bank)
Nombre de la variable: region_name
Tipo de dato: object
Descripción: Nombre de la región geográfica según clasificación del Banco Mundial.
Nombre de la variable: region_code
Tipo de dato: object
Descripción: Código de la región.
Nombre de la variable: country_name
Tipo de dato: object
Descripción: Nombre del país.
Nombre de la variable: country_code
Tipo de dato: object
Descripción: Código ISO del país.
Nombre de la variable: reporting_year
Tipo de dato: int64
Descripción: Año de referencia del indicador reportado.
Nombre de la variable: reporting_level
Tipo de dato: object
Descripción: Nivel del reporte (nacional, urbano, rural, etc.).
Nombre de la variable: survey_acronym
Tipo de dato: object
Descripción: Sigla o acrónimo de la encuesta utilizada.
Nombre de la variable: survey_coverage
Tipo de dato: object
Descripción: Tipo de cobertura de la encuesta (nacional, parcial, urbana, etc.).
Nombre de la variable: survey_year
Tipo de dato: float64
Descripción: Año de la encuesta, puede ser decimal o aproximado.
Nombre de la variable: welfare_type
Tipo de dato: object
Descripción: Tipo de bienestar usado (ingreso, consumo, etc.).
Nombre de la variable: survey_comparability
Tipo de dato: int64
Descripción: Indicador numérico de comparabilidad entre encuestas.
Nombre de la variable: comparable_spell
Tipo de dato: object
Descripción: Grupo de comparabilidad temporal de encuestas.
Nombre de la variable: poverty_line
Tipo de dato: int64
Descripción: Línea de pobreza en unidades internacionales (USD PPP o locales).
Nombre de la variable: headcount
Tipo de dato: float64
Descripción: Proporción de personas debajo de la línea de pobreza (poverty headcount).
Nombre de la variable: poverty_gap
Tipo de dato: float64
Descripción: Brecha de pobreza promedio.
Nombre de la variable: poverty_severity
Tipo de dato: float64
Descripción: Severidad de la pobreza (índice FGT2).
Nombre de la variable: watts
Tipo de dato: float64
Descripción: Estimación de bienestar (Watts index).
Nombre de la variable: mean
Tipo de dato: float64
Descripción: Media del ingreso/consumo per cápita.
Nombre de la variable: median
Tipo de dato: float64
Descripción: Mediana del ingreso/consumo per cápita.
Nombre de la variable: mld
Tipo de dato: float64
Descripción: Mean Log Deviation (desigualdad).
Nombre de la variable: gini
Tipo de dato: float64
Descripción: Índice de Gini de desigualdad.
Nombre de la variable: polarization
Tipo de dato: float64
Descripción: Medida de polarización económica.
Nombre de la variable: decile1
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 1.
Nombre de la variable: decile2
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 2.
Nombre de la variable: decile3
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 3.
Nombre de la variable: decile4
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 4.
Nombre de la variable: decile5
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 5.
Nombre de la variable: decile6
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 6.
Nombre de la variable: decile7
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 7.
Nombre de la variable: decile8
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 8.
Nombre de la variable: decile9
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 9.
Nombre de la variable: decile10
Tipo de dato: float64
Descripción: Ingreso/consumo promedio del decil 10.
Nombre de la variable: cpi
Tipo de dato: float64
Descripción: Índice de Precios al Consumidor usado para ajustar valores.
Nombre de la variable: ppp
Tipo de dato: float64
Descripción: Paridad de Poder Adquisitivo (Purchasing Power Parity).
Nombre de la variable: reporting_pop
Tipo de dato: float64
Descripción: Población utilizada para el cálculo del indicador.
Nombre de la variable: reporting_gdp
Tipo de dato: float64
Descripción: Producto Interno Bruto del país para el año reportado.
Nombre de la variable: reporting_pce
Tipo de dato: float64
Descripción: Consumo per cápita reportado.
Nombre de la variable: is_interpolated
Tipo de dato: bool
Descripción: Indica si los valores fueron interpolados.
Nombre de la variable: distribution_type
Tipo de dato: object
Descripción: Tipo de distribución usada (ej. “Lorenz”, “paramétrica”).
Nombre de la variable: spl
Tipo de dato: float64
Descripción: Severe Poverty Line (línea de pobreza severa).
Nombre de la variable: spr
Tipo de dato: float64
Descripción: Severe Poverty Rate (tasa de pobreza severa).
Nombre de la variable: pg
Tipo de dato: float64
Descripción: Poverty Gap (otra versión o línea alternativa).



Base datos dengue 2
Nombre de la variable: date
Tipo de dato: datetime64[ns]
Descripción: Fecha del registro reportado.
Nombre de la variable: date_lab
Tipo de dato: object
Descripción: Fecha asociada al laboratorio o procesamiento (formato texto).
Nombre de la variable: who_region
Tipo de dato: object
Descripción: Código de la región según la clasificación de la OMS.
Nombre de la variable: who_region_long
Tipo de dato: object
Descripción: Nombre completo de la región según la OMS.
Nombre de la variable: country
Tipo de dato: object
Descripción: Nombre del país reportante.
Nombre de la variable: iso3
Tipo de dato: object
Descripción: Código ISO 3 del país.
Nombre de la variable: cases
Tipo de dato: float64
Descripción: Número total de casos reportados en el período.
Nombre de la variable: confirmed_cases
Tipo de dato: float64
Descripción: Número de casos confirmados por laboratorio en el período.
Nombre de la variable: severe_cases
Tipo de dato: float64
Descripción: Número de casos severos reportados en el período.
Nombre de la variable: deaths
Tipo de dato: float64
Descripción: Número de muertes reportadas en el período.
Nombre de la variable: cfr
Tipo de dato: float64
Descripción: Case Fatality Ratio (proporción de muertes respecto a casos).
Nombre de la variable: prop_sev
Tipo de dato: float64
Descripción: Proporción de casos severos respecto al total de casos.
Nombre de la variable: cfr_ci_lower
Tipo de dato: float64
Descripción: Límite inferior del intervalo de confianza del CFR (95%).
Nombre de la variable: cfr_ci_upper
Tipo de dato: float64
Descripción: Límite superior del intervalo de confianza del CFR (95%).
Nombre de la variable: prop_sev_ci_lower
Tipo de dato: float64
Descripción: Límite inferior del intervalo de confianza de la proporción de casos severos (95%).
Nombre de la variable: prop_sev_ci_upper
Tipo de dato: float64
Descripción: Límite superior del intervalo de confianza de la proporción de casos severos (95%).



BASE DE DATOS DENGUE 1
Nombre de la variable: adm_0_name
Tipo de dato: object
Descripción: Nombre del país o región a nivel administrativo 0.

Nombre de la variable: adm_1_name
Tipo de dato: float64
Descripción: Código o identificador para la división administrativa de nivel 1 (estado/provincia).

Nombre de la variable: adm_2_name
Tipo de dato: float64
Descripción: Código o identificador para la división administrativa de nivel 2 (municipio/distrito).

Nombre de la variable: full_name
Tipo de dato: object
Descripción: Nombre completo de la ubicación combinando niveles administrativos.

Nombre de la variable: ISO_A0
Tipo de dato: object
Descripción: Código ISO del país (nivel 0).

Nombre de la variable: FAO_GAUL_code
Tipo de dato: int64
Descripción: Código GAUL asignado por FAO para la unidad administrativa.

Nombre de la variable: RNE_iso_code
Tipo de dato: object
Descripción: Código ISO utilizado por RNE para la región o país.

Nombre de la variable: IBGE_code
Tipo de dato: float64
Descripción: Código IBGE (Brasil) para la unidad administrativa.

Nombre de la variable: calendar_start_date
Tipo de dato: object
Descripción: Fecha de inicio del periodo de calendario (formato AAAA-MM-DD).

Nombre de la variable: calendar_end_date
Tipo de dato: object
Descripción: Fecha de fin del periodo de calendario (formato AAAA-MM-DD).

Nombre de la variable: Year
Tipo de dato: int64
Descripción: Año del periodo de reporte.

Nombre de la variable: dengue_total
Tipo de dato: float64
Descripción: Número total de casos de dengue reportados en el periodo.

Nombre de la variable: case_definition_standardised
Tipo de dato: object
Descripción: Definición estandarizada del caso de dengue utilizada en el reporte.

Nombre de la variable: S_res
Tipo de dato: object
Descripción: Resolución espacial (nivel de detalle geográfico).

Nombre de la variable: T_res
Tipo de dato: object
Descripción: Resolución temporal (nivel de detalle temporal).

Nombre de la variable: UUID
Tipo de dato: object
Descripción: Identificador único universal para cada registro.


Base de la tuberculisis
Diccionario TB - Variables Clave (Casos, Incidencia, Mortalidad, Resultados)
Nombre de la variable: rxsupport_community_succ
Categoría: Community engagement
Lista de códigos: No aplica
Descripción: Total number of patients who were cured or who completed treatment among the cases who started TB treatment and who received any form of treatment adherence support from community health workers / community volunteers in the Basic Management Units with data on community treatment adherence support

Nombre de la variable: c_newinc_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Case notification rate, which is the total of new and relapse cases and cases with unknown previous TB treatment history per 100 000 population (calculated)

Nombre de la variable: e_inc_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence (all forms) per 100 000 population

Nombre de la variable: e_inc_100k_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence (all forms) per 100 000 population, high bound

Nombre de la variable: e_inc_100k_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence (all forms) per 100 000 population, low bound

Nombre de la variable: e_inc_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of incident cases (all forms)

Nombre de la variable: e_inc_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of incident cases (all forms), high bound

Nombre de la variable: e_inc_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of incident cases (all forms), low bound

Nombre de la variable: e_inc_rr_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of rifampicin resistant TB (absolute number)

Nombre de la variable: e_inc_rr_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of rifampicin resistant TB (absolute number): high bound

Nombre de la variable: e_inc_rr_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of rifampicin resistant TB (absolute number): low bound

Nombre de la variable: e_inc_tbhiv_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive per 100 000 population

Nombre de la variable: e_inc_tbhiv_100k_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive per 100 000 population, high bound

Nombre de la variable: e_inc_tbhiv_100k_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive per 100 000 population, low bound

Nombre de la variable: e_inc_tbhiv_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive

Nombre de la variable: e_inc_tbhiv_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive, high bound

Nombre de la variable: e_inc_tbhiv_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated incidence of TB cases who are HIV-positive, low bound

Nombre de la variable: e_mort_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms) per 100 000 population

Nombre de la variable: e_mort_100k_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms) per 100 000 population, high bound

Nombre de la variable: e_mort_100k_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms) per 100 000 population, low bound

Nombre de la variable: e_mort_exc_tbhiv_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms, excluding HIV) per 100 000 population

Nombre de la variable: e_mort_exc_tbhiv_100k_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms, excluding HIV), per 100 000 population, high bound

Nombre de la variable: e_mort_exc_tbhiv_100k_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases (all forms, excluding HIV), per 100 000 population, low bound

Nombre de la variable: e_mort_exc_tbhiv_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms, excluding HIV)

Nombre de la variable: e_mort_exc_tbhiv_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms, excluding HIV), high bound

Nombre de la variable: e_mort_exc_tbhiv_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms, excluding HIV), low bound

Nombre de la variable: e_mort_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms)

Nombre de la variable: e_mort_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms), high bound

Nombre de la variable: e_mort_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB (all forms), low bound

Nombre de la variable: e_mort_tbhiv_100k
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases who are HIV-positive, per 100 000 population

Nombre de la variable: e_mort_tbhiv_100k_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases who are HIV-positive, per 100 000 population, high bound

Nombre de la variable: e_mort_tbhiv_100k_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated mortality of TB cases who are HIV-positive, per 100 000 population, low bound

Nombre de la variable: e_mort_tbhiv_num
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB in people who are HIV-positive

Nombre de la variable: e_mort_tbhiv_num_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB in people who are HIV-positive, high bound

Nombre de la variable: e_mort_tbhiv_num_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of deaths from TB in people who are HIV-positive, low bound

Nombre de la variable: e_rr_in_notified_labconf_pulm
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of RR-TB cases among notified bacteriologically confirmed pulmonary TB cases

Nombre de la variable: e_rr_in_notified_labconf_pulm_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of RR-TB cases among notified bacteriologically confirmed pulmonary TB cases: high bound

Nombre de la variable: e_rr_in_notified_labconf_pulm_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated number of RR-TB cases among notified bacteriologically confirmed pulmonary TB cases: low bound

Nombre de la variable: e_rr_pct_new
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of new TB cases with rifampicin resistant TB

Nombre de la variable: e_rr_pct_new_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of new TB cases with rifampicin resistant TB: high bound

Nombre de la variable: e_rr_pct_new_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of new TB cases with rifampicin resistant TB: low bound

Nombre de la variable: e_rr_pct_ret
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of previously treated TB cases with rifampicin resistant TB

Nombre de la variable: e_rr_pct_ret_hi
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of previously treated TB cases with rifampicin resistant TB: high bound

Nombre de la variable: e_rr_pct_ret_lo
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Estimated percentage of previously treated TB cases with rifampicin resistant TB: low bound

Nombre de la variable: source_rr_new
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Method used to estimate proportion of new TB patients with rifampicin-resistant TB

Nombre de la variable: source_rr_ret
Categoría: Estimates
Lista de códigos: No aplica
Descripción: Method used to estimate proportion of previously treated TB patients with rifampicin-resistant TB

Nombre de la variable: c_newinc
Categoría: Notification
Lista de códigos: No aplica
Descripción: Total of new and relapse cases and cases with unknown previous TB treatment history

Nombre de la variable: newrel_art
Categoría: Notification
Lista de códigos: No aplica
Descripción: HIV-positive new and relapse (or all, if newrel_tbhiv_flg = 0 and year > 2015) TB patients started or continued on antiretroviral therapy

Nombre de la variable: newrel_art_014
Categoría: Notification
Lista de códigos: No aplica
Descripción: Number of HIV-positive new and relapse TB patients aged 0-14 years who started or continued on antiretroviral therapy

Nombre de la variable: newrel_f014
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 0-14 years

Nombre de la variable: newrel_f04
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 0-4 years

Nombre de la variable: newrel_f1014
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 10-14 years

Nombre de la variable: newrel_f1519
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 15-19 years

Nombre de la variable: newrel_f1524
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 15-24 years

Nombre de la variable: newrel_f15plus
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 15 years and over

Nombre de la variable: newrel_f2024
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 20-24 years

Nombre de la variable: newrel_f2534
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 25-34 years

Nombre de la variable: newrel_f3544
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 35-44 years

Nombre de la variable: newrel_f4554
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 45-54 years

Nombre de la variable: newrel_f514
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 5-14 years

Nombre de la variable: newrel_f5564
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 55-64 years

Nombre de la variable: newrel_f59
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 5-9 years

Nombre de la variable: newrel_f65
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females aged 65 years and over

Nombre de la variable: newrel_fu
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): females age unknown

Nombre de la variable: newrel_hivpos
Categoría: Notification
Lista de códigos: No aplica
Descripción: Number of new and relapse  (or all, if newrel_tbhiv_flg = 0 and year > 2015) TB patients recorded as HIV-positive

Nombre de la variable: newrel_hivpos_014
Categoría: Notification
Lista de códigos: No aplica
Descripción: Number of new and relapse TB patients aged 0-14 years recorded as HIV-positive

Nombre de la variable: newrel_hivtest
Categoría: Notification
Lista de códigos: No aplica
Descripción: Number of new and relapse (or all, if newrel_tbhiv_flg = 0 and year > 2015) TB patients tested for HIV at the time of TB diagnosis or with known HIV status at the time of TB diagnosis

Nombre de la variable: newrel_hivtest_014
Categoría: Notification
Lista de códigos: No aplica
Descripción: Number of new and relapse TB patients aged 0-14 years tested for HIV at the time of TB diagnosis or with known HIV status at the time of TB diagnosis

Nombre de la variable: newrel_m014
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 0-14 years

Nombre de la variable: newrel_m04
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 0-4 years

Nombre de la variable: newrel_m1014
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 10-14 years

Nombre de la variable: newrel_m1519
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 15-19 years

Nombre de la variable: newrel_m1524
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 15-24 years

Nombre de la variable: newrel_m15plus
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 15 years and over

Nombre de la variable: newrel_m2024
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 20-24 years

Nombre de la variable: newrel_m2534
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 25-34 years

Nombre de la variable: newrel_m3544
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 35-44 years

Nombre de la variable: newrel_m4554
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 45-54 years

Nombre de la variable: newrel_m514
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 5-14 years

Nombre de la variable: newrel_m5564
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 55-64 years

Nombre de la variable: newrel_m59
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 5-9 years

Nombre de la variable: newrel_m65
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males aged 65 years and over

Nombre de la variable: newrel_mu
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): males age unknown

Nombre de la variable: newrel_sexunk014
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): sex unknown, aged 0-14 years

Nombre de la variable: newrel_sexunk04
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): sex unknown, aged 0-4 years

Nombre de la variable: newrel_sexunk15plus
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): sex unknown, aged 15 years and over

Nombre de la variable: newrel_sexunk514
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): sex unknown, aged 5-14 years

Nombre de la variable: newrel_sexunkageunk
Categoría: Notification
Lista de códigos: No aplica
Descripción: New and relapse cases (but only new cases if rel_in_agesex_flg = 0): sex unknown, age unknown

Nombre de la variable: newrel_tbhiv_flg
Categoría: Notification
Lista de códigos: 0=No; 1=Yes.
Descripción: Are data on HIV testing, HIV positivity and provision of antiretroviral therapy (ART) restricted to new and relapse TB cases only?

Nombre de la variable: c_new_snep_tsr
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Treatment success rate for new pulmonary smear-negative/extrapulmonary/smear unknown/smear not done cases, percent  (not used after 2011)

Nombre de la variable: c_new_sp_tsr
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Treatment success rate for new pulmonary smear-positive (and/or culture-positive) cases, percent  (not used after 2011)

Nombre de la variable: c_new_tsr
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Treatment success rate for all new cases (including relapse cases if rel_with_new_flg = 1), percent

Nombre de la variable: c_ret_tsr
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Treatment success rate for re-treatment cases (excluding relapse cases if rel_with_new_flg = 1), percent

Nombre de la variable: c_tbhiv_tsr
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Treatment success rate for HIV-positive TB cases, percent

Nombre de la variable: hiv_new_snep_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-negative/extrapulmonary/smear unknown/smear not done HIV-positive TB cases: died  (not used after 2011)

Nombre de la variable: hiv_new_snep_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-negative/extrapulmonary/smear unknown/smear not done HIV-positive TB cases: failed (not used after 2011)

Nombre de la variable: hiv_new_sp_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-positive (and/or culture-positive) HIV-positive TB cases: died (not used after 2011)

Nombre de la variable: hiv_new_sp_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-positive (and/or culture-positive) HIV-positive TB cases: failed (not used after 2011)

Nombre de la variable: hiv_ret_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for re-treatment HIV-positive TB cases: died (not used after 2011)

Nombre de la variable: hiv_ret_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for re-treatment HIV-positive TB cases: failed (not used after 2011)

Nombre de la variable: mdr_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for MDR-TB cases: died

Nombre de la variable: mdr_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for MDR-TB cases: treatment failed

Nombre de la variable: mdr_succ
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for MDR-TB cases: treatment success (Cured or treatment completed)

Nombre de la variable: new_snep_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-negative/extrapulmonary/smear unknown/smear not done cases: died (not used after 2011)

Nombre de la variable: new_snep_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-negative/extrapulmonary/smear unknown/smear not done cases: failed (not used after 2011)

Nombre de la variable: new_sp_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-positive (and/or culture-positive) cases: died (not used after 2011)

Nombre de la variable: new_sp_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for new pulmonary smear-positive (and/or culture-positive) cases: failed (not used after 2011)

Nombre de la variable: newrel_coh
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for all new and relapse cases (but only new cases if rel_with_new_flg = 0): cohort size

Nombre de la variable: newrel_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for all new and relapse cases (but only new cases if rel_with_new_flg = 0): died

Nombre de la variable: newrel_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for all new and relapse cases (but only new cases if rel_with_new_flg = 0): treatment failed

Nombre de la variable: newrel_lost
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for all new and relapse cases (but only new cases if rel_with_new_flg = 0): lost to follow-up

Nombre de la variable: newrel_succ
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for all new and relapse cases (but only new cases if rel_with_new_flg = 0): treatment success (cured or treatment completed)

Nombre de la variable: ret_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for re-treatment cases: died (not used after 2011)

Nombre de la variable: ret_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for re-treatment cases: failed (not used after 2011)

Nombre de la variable: ret_nrel_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for previously treated patients (excluding relapse cases if rel_with_new_flg = 1): died

Nombre de la variable: ret_nrel_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for previously treated patients (excluding relapse cases if rel_with_new_flg = 1): treatment failed

Nombre de la variable: ret_nrel_succ
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for previously treated patients (excluding relapse cases if rel_with_new_flg = 1): treatment success (cured or treatment completed)

Nombre de la variable: tbhiv_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for HIV-positive TB cases, all types: died

Nombre de la variable: tbhiv_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for HIV-positive TB cases, all types: treatment failed

Nombre de la variable: tbhiv_succ
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for HIV-positive TB cases, all types: treatment success (cured or treatment completed)

Nombre de la variable: xdr_died
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for XDR-TB cases: number died

Nombre de la variable: xdr_fail
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for XDR-TB cases: number whose treatment failed

Nombre de la variable: xdr_succ
Categoría: Outcomes
Lista de códigos: No aplica
Descripción: Outcomes for XDR-TB cases: treatment success (Cured or treatment completed)

Nombre de la variable: died
Categoría: Outcomes by age group and sex
Lista de códigos: No aplica
Descripción: Outcomes: died

Nombre de la variable: fail
Categoría: Outcomes by age group and sex
Lista de códigos: No aplica
Descripción: Outcomes: treatment failed

Nombre de la variable: succ
Categoría: Outcomes by age group and sex
Lista de códigos: No aplica
Descripción: Outcomes: treatment success (Cured or treatment completed)

Nombre de la variable: tsr
Categoría: Outcomes by age group and sex
Lista de códigos: No aplica
Descripción: Treatment success rate as a percentage

Nombre de la variable: newrel_prisoners
Categoría: Policies and services
Lista de códigos: No aplica
Descripción: (if ident_pris=1) Number of new and relapse TB cases registered in prisons

Nombre de la variable: newrel_ep_labconf
Categoría: Zoonotic TB
Lista de códigos: No aplica
Descripción: (if ep_spec_available=1) Among the new and relapse extrapulmonary TB cases reported in new_ep and ret_rel_ep, the number of cases that were bacteriologically confirmed, i.e. by culture or molecular technologies

Nombre de la variable: newrel_ep_mbovis
Categoría: Zoonotic TB
Lista de códigos: No aplica
Descripción: (if ep_spec_available=1) Among extrapulmonary TB cases with test results for speciation reported in newrel_ep_spec, number of cases identified as having Mycobacterium bovis

Nombre de la variable: newrel_ep_spec
Categoría: Zoonotic TB
Lista de códigos: No aplica
Descripción: (if ep_spec_available=1) Among bacteriologically confirmed extrapulmonary TB cases reported in newrel_ep_labconf, number of cases with test results for the speciation of the Mycobacterium tuberculosis complex

Nombre de la variable: newrel_pulm_mbovis
Categoría: Zoonotic TB
Lista de códigos: No aplica
Descripción: (if pulm_spec_available=1) Among pulmonary cases with test results for speciation reported in newrel_pulm_spec, number of cases identified as having Mycobacterium bovis

Nombre de la variable: newrel_pulm_spec
Categoría: Zoonotic TB
Lista de códigos: No aplica
Descripción: (if pulm_spec_available=1) Among bacteriologically confirmed new and relapse pulmonary TB cases, number of cases with test results for the speciation of the Mycobacterium tuberculosis complex

Base del HIV 

Diccionario de Variables VIH
Nombre de la variable: Number of people living with HIV who know their HIV status
Tipo de dato: Float
Categorías: All ages, Children (0–14), Women (15+), Men (15+), Adults (15+)
Valores: High, Estimate, Low
Descripción: Número de personas que viven con VIH y conocen su estado serológico, desagregado por grupos de edad y sexo, con rangos de incertidumbre (alto, estimado, bajo).
BASE GASTO DEL PID EN SALUD DE CADA PAIS

Data Source
Tipo: object
Descripción: En la primera fila contiene la fecha de actualización del dataset. En las filas de datos contiene el nombre del país o queda en blanco.

Indicadores del desarrollo mundial
Tipo: object
Descripción: En la primera fila contiene el nombre del campo. En las filas de datos contiene el código de país o código de región (ej.: CRI, USA, LAC, AFE).
Unnamed: 2
Tipo: object
Descripción: Nombre del indicador: "Gasto corriente en salud (% del PIB)".
Columnas de años (Unnamed: 3 a Unnamed: 27)
Cada columna corresponde al valor del indicador para un año específico:
Unnamed: 3: float64 → Año 2000
Unnamed: 4: float64 → Año 2001
Unnamed: 5: float64 → Año 2002
Unnamed: 6: float64 → Año 2003
Unnamed: 7: float64 → Año 2004
Unnamed: 8: float64 → Año 2005
Unnamed: 9: float64 → Año 2006
Unnamed: 10: float64 → Año 2007
Unnamed: 11: float64 → Año 2008
Unnamed: 12: float64 → Año 2009
Unnamed: 13: float64 → Año 2010
Unnamed: 14: float64 → Año 2011
Unnamed: 15: float64 → Año 2012
Unnamed: 16: float64 → Año 2013
Unnamed: 17: float64 → Año 2014
Unnamed: 18: float64 → Año 2015
Unnamed: 19: float64 → Año 2016
Unnamed: 20: float64 → Año 2017
Unnamed: 21: float64 → Año 2018
Unnamed: 22: float64 → Año 2019
Unnamed: 23: float64 → Año 2020
Unnamed: 24: float64 → Año 2021
Unnamed: 25: float64 → Año 2022
Unnamed: 26: float64 → Año 2023
Unnamed: 27: float64 → Año 2024 (si aplica).


Referencias Bibliográficas de las bases de datos
1. Base Dengue 1 – WHO
World Health Organization. (2025). Dengue global data [Dataset]. https://worldhealthorg.shinyapps.io/dengue_global/
World Health Organization. (2025). Dengue global data [Dataset]. Retrieved November 12, 2025, from https://worldhealthorg.shinyapps.io/dengue_global/
2. Base Dengue 2 – OpenDengue
OpenDengue. (2025). National extract V1.3 [Dataset]. https://opendengue.org/
3. Base Tuberculosis – Our World in Data
Our World in Data. (2025). Number of tuberculosis cases [Dataset]. https://ourworldindata.org/grapher/number-of-tuberculosis-cases
4. Base HIV – UNAIDS
UNAIDS. (2025). HIV estimates with uncertainty bounds, 1990–present [Dataset]. https://www.unaids.org/en/resources/documents/2025/HIV_estimates_with_uncertainty_bounds_1990-present
5. Base Gasto en Salud (% PIB) – Banco Mundial
World Bank. (2025). Current health expenditure (% of GDP) [Dataset]. https://datos.bancomundial.org/indicador/SH.XPD.CHEX.GD.ZS
(Nota: Aunque la conversión a JSON fue autorizada, en la referencia APA se cita la fuente original.)
6. Base Índice de Pobreza – Banco Mundial (PIP)
World Bank. (2025). Global poverty index [Dataset]. https://pip.worldbank.org/

