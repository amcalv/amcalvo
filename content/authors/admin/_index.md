---
# Display name
name: Alejandro Martínez-Calvo

# Username (this should match the folder name)
authors:
- admin

# Is this the primary user of the site?
superuser: true

# Role/position
role: HFSP fellow (Associate Research Scholar)

# Organizations/Affiliations
organizations:
- name: Princeton University
  url: "https://www.princeton.edu"

# Short bio (displayed in user profile at end of posts)
bio: I am an <a href="https://www.hfsp.org">HFSP (Human Frontier Science Program)</a> fellow at the <a href="https://pcts.princeton.edu/">Princeton Center for Theoretical Science</a> and the <a href="https://cbe.princeton.edu">Department of Chemical and Biological Engineering</a> (<a href="https://dattalab.princeton.edu">Datta Lab</a>) at <a href="https://www.princeton.edu">Princeton University</a>. I obtained my Ph.D. in Fluid Dynamics under the supervision of <a href="http://fluidosuc3m.es/people/asevilla/">Prof. Alejandro Sevilla</a> at Universidad Carlos III de Madrid, supported by a FPU doctoral fellowship.

interests:
- Biological Physics
- Soft Active Matter
- Fluid Dynamics

education:
  courses:
  - course: PhD in Fluid Mechanics
    institution: Universidad Carlos III de Madrid
    year: 2020
  - course: MSc in Applied Mathematics
    institution: Universidad Carlos III de Madrid and Universidad Politécnica de Madrid
    year: 2017
  - course: BSc in Mechanical Engineering
    institution: Universidad Carlos III de Madrid
    year: 2015

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/widgets/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: mailto:amcalvo@ing.uc3m.es   #'#contact'  # For a direct email link, use "mailto:amcalvo@ing.uc3m.es"
#- icon: twitter
#  icon_pack: fab
#  link: https://twitter.com/almcalvo
- icon: google-scholar
  icon_pack: ai
  link: https://scholar.google.es/citations?user=ThiJBj8AAAAJ&hl=es
- icon: researchgate
  icon_pack: ai
  link: https://www.researchgate.net/profile/A_Martinez-Calvo
- icon: arxiv
  icon_pack: ai
  link: https://arxiv.org/a/martinezcalvo_a_1.html
- icon: orcid
  icon_pack: ai
  link: https://orcid.org/0000-0002-2109-8145
#- icon: github
#  icon_pack: fab
#  link: https://github.com/amcalv
# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.  
# - icon: cv
#   icon_pack: ai
#   link: files/cv.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""
  
# Organizational groups that you belong to (for People widget)
#   Set this to `[]` or comment out if you are not using People widget.  
user_groups:
- Researchers
- Visitors
---
I am an <a href="https://www.hfsp.org">HFSP (Human Frontier Science Program)</a> fellow at the <a href="https://pcts.princeton.edu/">Princeton Center for Theoretical Science</a> and the <a href="https://cbe.princeton.edu">Department of Chemical and Biological Engineering</a> (<a href="https://dattalab.princeton.edu">Datta Lab</a>) at <a href="https://www.princeton.edu">Princeton University</a>. I obtained my Ph.D. in Fluid Dynamics under the supervision of <a href="http://fluidosuc3m.es/people/asevilla/">Prof. Alejandro Sevilla</a> at Universidad Carlos III de Madrid, supported by a FPU doctoral fellowship.

My research is framed within the fields of soft/active matter, biological physics, and fluid dynamics. So far, I have studied systems involving small-scale interfacial flows, bulk and interfacial rheology, elasticity, and membrane dynamics. Currently, I am interested in several research areas within the context of biophysics and living matter, namely the dynamics of eukaryotic cells and tissues, and the physics of bacteria in complex habitats. I employ theory and accurate numerical methods to unravel the physics of these complex systems.

{{ $asset := resources.Get "/hfsp.png" }}
{{ $img := $asset.Fit "600x400" }}
<figure class="image is-3by2">
  <img alt="Yellow Duck" src="{{ $img.RelPermalink }}" />
</figure>
