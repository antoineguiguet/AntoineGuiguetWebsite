---
title: Citizen Science
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Explorer les galles ensemble
      text: |-
        Au carrefour de l'entomologie et de la botanique, les galles sont de formidables portes d’entrée vers l’observation de la biodiversité. Longtemps négligées, elles suscitent aujourd’hui un regain d’intérêt chez les naturalistes. Afin de promouvoir la cécidologie et de mieux faire connaître les insectes et autres organismes qui les induisent, mais dans le cadre de mes recherches sur ces organismes, je développe des projets de science participative.

        En vue de d'encourager le développement, je m'investis dans création d'un réseau de cécidologues scientifiques et amateurs. Ainsi, avec [Antoine Branca](https://www.egce.universite-paris-saclay.fr/?p=15507) nous avons créé [<font color="#550000">la liste de diffusion **Galla Gallica** dans l'objectif de permettre aux naturalistes et chercheurs francophones d’échanger observations, identifications et actualités.</font>](#liste) Ensuite je m'appuie sur les réseaux sociaux naturalistes. [<font color="#74ab01"> Sur **iNaturalist**, j’ai lancé un projet dédié aux galles, auquel chacun peut contribuer en partageant ses observations, en parallèle d'autres projets déjà existants auxquels je collabore.</font>](#iNaturalist) [<font color="#3d8a8b">Sur **INPN Espèces**, je poste des quêtes pour guider les naturalistes dans la recherche de galles spécifiques.</font>](#INPN) 
        
        Pour accompagner ces démarches, [<font color="#784421"> je produit des ressources pour aider les cécidologues amateurs, telles que des **guides d'identification des galles** , ou des **recommandations pour l’élevage** des insectes cécidogènes.</font>](#guide)


    design:
      columns: '1'
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: liste
    content: 
      title: <font color="#550000">Liste de diffusion Galla Gallica</font> 
      subtitle: 
      text: |-
        Cette liste de diffusion a pour objectif de mettre en relation les chercheurs et naturalistes francophones s’intéressant aux galles de plantes, ou cécidies. Elle vise à faciliter les échanges et la collaboration en permettant 
        - la diffusion de demandes d’informations scientifiques ou techniques,  
        - le partage de publications récentes et de ressources bibliographiques,  
        - les demandes d’envoi de spécimens,  
        - l’organisation de sorties de terrain et d’autres événements communs,  
        - le signalement et la discussion d’observations de terrain intéressantes, 
        - le partage d’opportunités (appels à projets, offres de stage ou de collaboration), 
        - et plus largement, la création d’un réseau dynamique autour de l’étude des galles.

      filters:
        folders:
          - CitSci1
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: true
    # Choose a color such as from https://html-color-codes.info
      background:
      #  color: '#cfe2f3'
       gradient_start: '#bd9c9c'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: iNaturalist
    content:
      title: <font color="#74ab01">Projets iNaturalist</font>
      subtitle: 
      text: |-
        ## L'Observatoire francophone des Galles

        Ce projet a pour but de rassembler les observations de galles faites par les naturalistes francophones, sans restriction géographique. 

        **Comment participer ?**

        Pour rejoindre le projet, il suffit de : 
        1.  Avoir un compte sur iNaturalist. 
        2.  Devenir membre de l’[Observatoire francophone des Galles](https://www.inaturalist.org/projects/observatoire-francophone-des-galles). 
        3.  Annoter ses observations de galles : dans la barre de droite, sous Annotations, sélectionner "Galle" dans l’onglet "Signe de présence". 
        
        Une fois membre du projet, toutes vos observations de galles correctement annotées seront automatiquement intégrées au projet. 
        
        **Pourquoi un nouveau projet iNaturalist ?** 
        
        Ce projet est complémentaire des initiatives existantes comme Galles de France ou European Plant Gall Faunistics, qui sont limitées à certaines zones géographiques. Ici, toutes les observations de galles des membres effectuées partout dans le monde seront accessibles en un seul endroit, offrant une vue d’ensemble plus large et facilitant les échanges. 
        
        **Un espace collaboratif** 

        La rubrique "Journal du projet" nous permettra en tant qu’administrateurs du projet de partager des objectifs d’observation et de mettre en avant des observations remarquables. Ce projet peut ainsi devenir une sorte de réseau social du groupe Galla Gallica. Rendez-vous sur iNaturalist pour partager vos observations, si cela vous intéresse. 

      filters:
        folders:
          - CitSci2
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
    # Choose a color such as from https://html-color-codes.info
      background:
      #  color: '#f4cccc'
       gradient_start: '#c9df9c'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '20px', '0']

  - block: collection
    id: INPN
    content:
      title: <font color="#3d8a8b">Quêtes INPN Espèces</font>
      subtitle: 
      text: Lancé en mars 2021, le dispositif des quêtes [INPN Espèces](https://inpn.mnhn.fr/accueil/participer/inpn-especes) invite le grand public à participer, pendant une période courte et ciblée, à la recherche d’une espèce précise sur un territoire donné. L’objectif, recueillir des données naturalistes utiles aux chercheurs, en réponse à des besoins concrets identifiés dans le cadre de leurs travaux scientifiques. Ces quêtes sont une manière simple, concrète et stimulante de contribuer à la recherche en écologie et en biodiversité.
      filters:
        folders:
          - CitSci3
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: card
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
    # Choose a color such as from https://html-color-codes.info
      background:
    #  color: '#d9ead3'
       gradient_start: '#b4d2d2'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '0', '0']

  - block: collection
    id: guide
    content:
      title: <font color="#784421">Ressources pour l'étude des galles</font>
      subtitle: 
      text:  
      filters:
        folders:
          - CitSci4
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      # Choose your content listing view - here we use the `showcase` view
      view: showcase
      # For the Showcase view, do you want to flip alternate rows?
      flip_alt_rows: false
    # Choose a color such as from https://html-color-codes.info
      background:
    #  color: '#d9ead3'
       gradient_start: '#cbb6a9'
       gradient_end: '#ffffff'
       gradient_angle: 180
      spacing:
    # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '0', '0', '0']

#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: wasps.png
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen
---
