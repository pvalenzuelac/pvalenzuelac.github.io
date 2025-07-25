---
title: "Research"
layout: simple
---

<!-- Toggle abstract/bibtex -->
<script>
  function toggle_visibility(id) {
    var e = document.getElementById(id);
    if (e.style.display === 'none' || e.style.display === '') {
      e.style.display = 'block';
    } else {
      e.style.display = 'none';
    }
  }
</script>



<!-- Main content -->

You can find more about my projects in my [CV](../cv/cv_latest.pdf).

---
## Job Market Paper
- **Infrastructure Provision and Displacement: Evidence from the Interstate Highway System**
  <br/><span style="
              color: rgb(0,114,178); 
              font-weight: bold;
              "
              >
              Best Student Paper Prize 2024, Urban Economics Association.
          </span>
  <br/><span style="
              color: rgb(0,114,178); 
              font-weight: bold;
              "
            >
              Frank Lewis Memorial Prize for Best Student Paper 2025, CNEH.
            </span>
  <br/><span style="
              color: black;
              margin-top: -20px;
              "
              >
              Last version: February 2025. 
          </span>            
<div style="
  display: flex;
  gap: 0.5em;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: -20px;
  margin-left: 2.5em;"
  >

  <a href="../research/displacement_jmp.pdf" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Draft]
  </a>
  <span>·</span>
  <!--
  <a href="../data/yellowbook_maps.zip" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Yellow book data]
  </a>
  <span>·</span>
  -->
  <button onclick="toggle_visibility('abstract')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Show/Hide Abstract]
  </button>
  <span>·</span>

  <button onclick="toggle_visibility('bib1')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Bibtex]
  </button>

</div>


<!-- Abstract block -->
<div id="abstract" style="display:none; margin-top:10px; border:0px solid #ccc; padding:10px;">
  I study the long-run effects of displacement and neighborhood division by examining individuals affected by the construction of the Interstate Highway System. To do so, I track individuals over time by linking the 1940 census to administrative mortality records from 1995 to 2005. I find that displaced individuals die three months younger, are more likely to leave their neighborhoods, and reside in areas with lower socioeconomic characteristics at the time of death. I also find highly localized spillovers: individuals living within 100 meters of a highway are more likely to leave their neighborhoods and relocate to lower socioeconomic areas, yet they do not experience increased mortality. The neighborhoods where individuals relocate after displacement explain 30% of the displacement-mortality effect. Accounting for the mortality effects of displacement would have increased the cost of building the highway system by 10%. Together, these results enhance our understanding of the costs displacement imposes on individuals and their communities and provide new insights for the design of future infrastructure projects.
</div>

<!-- BibTeX block -->

<div id="bib1" style="display: none; margin-top: 10px;">
  <pre style="
    background-color: #f5f5f5;
    padding: 10px;
    font-family: monospace;
    font-size: 14px;
    border: 1px solid #ddd;
    border-radius: 4px;
    overflow-x: auto;
    white-space: pre;
  ">
@misc{valenzuela-casasempere2025displacement,
  title  = {Displacement and Infrastructure Provision: Evidence from the Interstate Highway System},  
  author = {Pablo Valenzuela-Casasempere},
  year   = {2025}
}
  </pre>
</div>


  

---
## Working papers
- **Neighborhood Evolution and Infrastructure Provision**
  <br/><span style="
              color: black;
              margin-top: -20px;
              "
              >
              Last version: October 2024. 
          </span>            
<div style="
  display: flex;
  gap: 0.5em;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: -20px;
  margin-left: 2.5em;"
  >

  <a href="../research/hwys_ES.pdf" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Draft]
  </a>
  <span>·</span>
  <button onclick="toggle_visibility('abstract2')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Show/Hide Abstract]
  </button>
  <span>·</span>

  <button onclick="toggle_visibility('bib2')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Bibtex]
  </button>
</div>


<!-- Abstract block -->
<div id="abstract2" style="display:none; margin-top:10px; border:0px solid #ccc; padding:10px;">
    This paper examines the long-run socioeconomic impact of highway construction on U.S. neighborhoods.
    I construct a balanced panel of neighborhood-level characteristics from 1930 to 2020 for 62 metropolitan areas by combining data from historical census records and decennial censuses.
    Neighborhood-level aggregates for 1930 and 1940 are created by geocoding address-level information from historical files and then aggregating the data to match census tract boundaries.
    Using a matched difference-in-differences design, I find that highway construction reduces the total population of neighborhoods.
    The effects are driven by a relative decline in the Black population, with no significant effect on the white population.
    There is no evidence of changes in rents, but homeownership rates decrease following highway construction.
    The analysis suggests that these effects are more pronounced in suburban areas and in neighborhoods with a low initial share of Black residents.
    Additionally, I find evidence of spillover effects on adjacent neighborhoods.  
    </div>

<!-- BibTeX block -->

<div id="bib2" style="display: none; margin-top: 10px;">
  <pre style="
    background-color: #f5f5f5;
    padding: 10px;
    font-family: monospace;
    font-size: 14px;
    border: 1px solid #ddd;
    border-radius: 4px;
    overflow-x: auto;
    white-space: pre;
  ">
@misc{valenzuela-casasempere2024neighborhoods,
  title  = {Neighborhood Evolution and Infrastructure Provision},  
  author = {Pablo Valenzuela-Casasempere},
  year   = {2024}
}
  </pre>
</div>




- **Does the College Bias of Agglomeration Externalities Vary Across the Work-Cycle and Time?**
  <br/><span style="
              color: black;
              margin-top: -20px;
              "
              >
              Last version: October 2024. 
          </span>            
<div style="
  display: flex;
  gap: 0.5em;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: -20px;
  margin-left: 2.5em;"
  >

  <a href="../research/wics.pdf" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Draft]
  </a>
  <span>·</span>
  <button onclick="toggle_visibility('abstract3')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Show/Hide Abstract]
  </button>
  <span>·</span>

  <button onclick="toggle_visibility('bib3')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Bibtex]
  </button>
</div>


<!-- Abstract block -->
<div id="abstract3" style="display:none; margin-top:10px; border:0px solid #ccc; padding:10px;">
    This paper documents the heterogeneous rise in the urban gradient of the college wage gap across workers of different ages between 1980 and 2019. 
    Using immigrants' enclaves from 1970 as source of identification, I find that the young workers have traditionally had a steeper relationship between college wage gap and city population than old workers. 
    Also, I find that the evolution of this urban gradient of the college wage gap has been larger for younger workers. 
    These findings are not caused by sorting in unobserved characteristics, by outliers in the wage distribution, or by compositional changes. 
    I show that the source of the increase in the urban component of the college wage gap is a shift in the occupational structure across the work-cycle and cities. 
    While old and young college workers have shifted away from highly-routinary-low-paying jobs, specially in more populated cities, young high school graduates’ occupational structure has remained unaltered since 1980.   
</div>

<!-- BibTeX block -->

<div id="bib3" style="display: none; margin-top: 10px;">
  <pre style="
    background-color: #f5f5f5;
    padding: 10px;
    font-family: monospace;
    font-size: 14px;
    border: 1px solid #ddd;
    border-radius: 4px;
    overflow-x: auto;
    white-space: pre;
  ">
@misc{valenzuela-casasempere2024wageineq,
  title  = {Does the College Bias of Agglomeration Externalities Vary Across the Work-Cycle and Time?},  
  author = {Pablo Valenzuela-Casasempere},
  year   = {2024}
}
  </pre>
</div>

---
## Work in progress
- **Immigrant Neighborhood Formation: Evidence from Canadian Cities**
  <br /> with [Pierre-Loup Beauregard](https://www.pierreloupbeauregard.org) and [Vedran Razmilic](https://economics.ubc.ca/profile/vedran-juraj-razmilic/).
  <br /> 
  <!--
   We analyze the formation of immigrant enclaves in Canada. We develop a quantitative model of internal city structure in which forward-looking individuals choose where to live and work at every period. We allow for heterogeneous preferences over endogenous amenities depending on immigration status. We exploit Canadian administrative tax files and estimate group-specific neighborhood valuation using a revealed preference approach. By exploiting the neighborhood-to-neighborhood transition of households in Canada, we document that the correlation of neighborhood valuations between foreign- and Canadian-born households is positive but far from unity. We then analyze counterfactual scenarios where households have the same preferences regardless of nationality and study the implications for income and urban segregation.
  -->


- **Human Capital Spillovers Across Cities** 
  <br/> with [Giulia Lo Forte](https://loforteg.github.io). 
<div style="
  display: flex;
  gap: 0.5em;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: -15px;
  margin-left: 2.5em;"
  >

  <a href="../research/hcs_slides.pdf" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Slides]
  </a>
</div>




  <!--
  This paper studies human capital spillovers among Spanish workers. Leveraging administrative matched employer-employee data for Spain between 2006 and 2020, we study whether the experience gained by workers in larger cities transfers to workers in smaller cities when they relocate. We find that, for workers in medium-sized cities, their three-year wage growth is 1.2 log points larger for each year of experience their coworkers accumulated in a large city. This positive knowledge spillover may mitigate the negative welfare effects of restricting the growth of large cities - an avenue we plan to explore in future research.
  -->
  <!--
- **Building a Nation Through Shared Experience: Evidence from First Nations’ Participation in WWI**
  <br/>
  <a id="hide8" href="#hide8" class="hide">[Show Abstract]</a>
  <a id="show8" href="#show8" class="show">[Hide Abstract]</a>
  <div class="details">
  This project examines First Nation assimilation in the U.S., leveraging participation in World War I and linked census data. I find that individuals who participated in the war are more likely to give their children Western names and to migrate to urban areas outside the reservation. Additionally, there is evidence of cultural transmission to other reservation residents and their children. Identification stems from the WWI draft and the influence of war propaganda.
  </div>
- **Aid and Urbanization in Africa**
  <br/> with [Sara Benetti](https://economics.ubc.ca/profile/sara-benetti/).
  <a id="hide9" href="#hide9" class="hide">[Show Abstract]</a>
  <a id="show9" href="#show9" class="show">[Hide Abstract]</a>
  <div class="details">
  The African continent is urbanizing rapidly, but at lower levels of industrialization compared to other regions. At the same time, the continent's reliance on international aid has increased over the past decades. Aid tends to be concentrated in urban areas due to capacity and infrastructure constraints. In this project, we plan to examine the role of international aid in driving the continent's rapid urbanization. 
  </div>
  -->
---
## Book Chapters 
- **Una Restricción Vehicular Inteligente para la Congestión y Contaminación de Santiago**
  <br /> with JP Montero, L. Basso, F. Sepúlveda, L. Cifuentes, and S. Vicuña. In Spanish.
  <br />  [[Draft]](../research/cap_pol_publicas.pdf) ·
  <button onclick="toggle_visibility('abstract4')" style="
  all: unset;
  color: black;
  text-decoration: underline;
  text-decoration-color: #6a7ba2;
  text-decoration-thickness: 2px;
  text-underline-offset: 4px;
  cursor: pointer;
  ">
    [Show/Hide Abstract]
  </button>
  <div id="abstract4" style="display:none; margin-top:10px; border:0px solid #ccc; padding:10px;">
    Ante los persistentes problemas de congestión y contaminación en la ciudad de Santiago, avanzamos en una propuesta de política pública de restricción vehicular que se construye a partir de iniciativas impulsadas en el pasado por el Ministerio de Medio Ambiente y el Ministerio de Transporte y Telecomunicaciones. Se trata de un diseño “inteligente”, porque: (i) lleva a un aumento importante (aunque menor que el máximo posible) de bienestar en la población, tanto por reducciones en tiempos de viaje como de contaminantes locales y globales; (ii) incluye medidas para distribuir los beneficios de la política en forma más equitativa entre los distintos grupos de ingreso; y (iii) tiene factibilidad política de implementación, ya que comparte elementos de propuestas existentes o bajo consideración. Nuestra propuesta base incluye una restricción de dos días a la semana (cuatro dígitos diarios) durante horas punta, con una opción de eximición, previo pago de un pase diario que depende del tipo de vehículo y época del año. De octubre a marzo, el pase diario estaría disponible a todo vehículo a un precio de $9.000. De abril a septiembre, el pase diario estaría disponible solo para vehículos que cumplan con la normativa de emisión Euro III. El total de la recaudación de los pases diarios se destina al transporte público, ya sea para mejorar su servicio (aumentos de frecuencia) y/o reducir sus tarifas. En caso que el 100% de la recaudación se destine a esto último, las tarifas caerían en 35%. 
  </div>



---
## Pre-doctoral work
- **Air Pollution and Road Safety**
  <br/><span style="
              color: black;
              margin-top: -20px;
              "
              >
              Last version: December 2017. 
          </span>            
<div style="
  display: flex;
  gap: 0.5em;
  align-items: center;
  flex-wrap: wrap;
  flex-direction: row;
  margin-top: -20px;
  margin-left: 2.5em;"
  >

  <a href="../research/ma_thesis.pdf" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Draft]
  </a>
  <span>·</span>
  <button onclick="toggle_visibility('abstract5')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Show/Hide Abstract]
  </button>
  <span>·</span>

  <button onclick="toggle_visibility('bib5')" style="
    all: unset;
    color: black;
    text-decoration: underline;
    text-decoration-color: #6a7ba2;
    text-decoration-thickness: 2px;
    text-underline-offset: 4px;
    cursor: pointer;">
    [Bibtex]
  </button>
</div>


<!-- Abstract block -->
<div id="abstract5" style="display:none; margin-top:10px; border:0px solid #ccc; padding:10px;">
    I link 6-hour air pollution exposure to the total number of car accidents in the city of Santiago by exploiting time-series variation from 2013 to 2016. 
    In order to identify the causal effect of CO exposure, I use plausible exogenous variation in atmospheric stability to instrument CO exposure. 
    I found a nonlinear relationship between CO exposure and the total number of car accidents. 
    This result is driven by nonfatal accidents. 
    Indeed, I do not find any impact on fatal accidents. 
    In addition, the results hold under a battery of robustness checks. 
    Although Santiago’s CO level is far below the international criteria of a hazardous level, I argue that reducing the average level of pollution leads to a sizable increase in social welfare due to a reduction in the number of car accidents.
  
</div>

<!-- BibTeX block -->

<div id="bib5" style="display: none; margin-top: 10px;">
  <pre style="
    background-color: #f5f5f5;
    padding: 10px;
    font-family: monospace;
    font-size: 14px;
    border: 1px solid #ddd;
    border-radius: 4px;
    overflow-x: auto;
    white-space: pre;
  ">
@misc{valenzuela-casasempere2017airpollution,
  title  = {Air Pollution and Road Safety},  
  author = {Pablo Valenzuela-Casasempere},
  year   = {2017}
}
  </pre>
</div>


