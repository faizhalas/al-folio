---
layout: page
permalink: /people/
title: people
description: people who have partnered with me in previous projects as well as those currently collaborating
nav: true
nav_order: 7
display_categories: [Project Collaborators, Academic Co-authors]
horizontal: false
---

{% assign projects = 
  [
    {
      "title": "Dr. Manika Lamba",
      "category": "Project Collaborators",
      "affiliation": "University of Oklahoma",
      "image": "https://lh6.googleusercontent.com/OZnsmmo1hRs3fVbT5a2xYAyDBq6sXb7WNiIob3mbfTxvvHNwyBor3WAV2XjQZ1YpBOa_v26xtilXiFFJhU5rP8ORgZnlAMrKM3gYQ0lowGljeNyg5qvDcRcqrvsNAX3tEhgJCpr2DooX_ZRsPO8L7YBEVHTnFSvSa8o0wr469nz1L8xtIut-RQ=w1280"
    },
    {
      "title": "Crissandra George",
      "category": "Project Collaborators",
      "affiliation": "Case Western Reserve University",
      "image": "https://lh5.googleusercontent.com/Al3Pl1C5AtjUW4dVH-j0qCnakJcY-T86aBwE3BPuHUDKehG5_0xV8D9guaZQiUCZSoZQqREdd0Hm2rIPm6XccPCoh5uHy16y2_ig7gGaISsmHpB-TcTpD7WLT-CkcF_HO14bA1hlU57IMXhKO-IhxsLYlDh_NuxYehxhCfatsfKHw-wzMcTVaQ=w1280"
    },
    {
      "title": "Yujia Wei",
      "category": "Project Collaborators",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "https://lh6.googleusercontent.com/ZBQUjnHdoMYMaaAEXILAHwviGbuvWNJwixstu9OpKH3DtleVv589M_TuvRWptdrWx0Za7PA_2_PrpMD8C_S_VeQqA300hdvJ-8dTa06UQW3_sjp80hUi6O2H1t5_he-0U-GqsTyRv0sNzJfAn1TyGhNOFZgGCW_K5Fac_tI-5FETl8oxgK1ebQ=w1280"
    },
    {
      "title": "Hewei Tang",
      "category": "Project Collaborators",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "https://lh4.googleusercontent.com/tEfq7gHdyh_bRXi4jgN2e5wnN9q046rF9-YWMTP64TaaIN8M0DLDI_XB37fePL5PiR958Y3d8Q3V73F8QsB-GyyYJkNYIs1FIJKipoQGdfpJsr_KH-jnDPPfZ7HlX0xiD5Arr_thtCOxnl8bpAAYhI4o3wYIB7vPk3B1exaRvGaRCqbykYt4qg=w1280"
    },
    {
      "title": "Tam Le",
      "category": "Project Collaborators",
      "affiliation": "University of Oklahoma",
      "image": "https://lh6.googleusercontent.com/dlJJcLRyY3pjmdvJGE8FucbO2o8HDjtEy951Oaji_NgUiQr0D44ILOG9ywAXFRCngQoIfoN3CwIMqoS3zUUChIlOk_YgkGwXV40oSb-tbzengBzQx4z59gpZLhHST3VUT4-t9M0oepRwtT_DRWF3q8QFLAKr5Xy_gr9dUrr00uAwrvx-6iJW_A=w1280"
    },
    {
      "title": "Prof. J. Stephen Downie",
      "category": "Academic Co-authors",
      "affiliation": "University of Illinois Urbana-Champaign",
      "image": "https://lh4.googleusercontent.com/kr07-yKStloqMgSqGA_QBCp1OR9I1OELim7qV3Fgt8BQbLAAtr66uf5qgo3QoTMPNFM-yDapLlDD_VwIrRJvRHCiuV3D_m8R4PiLK_CKzwH1c01DrtJi-m70V_BST8YHf_7MIAudarKpBBTjyzImVqsmSGNb0pKH78J5Pk5oQ37Ij67IVj_5nA=w1280"
    },
    {
      "title": "Mochammad Riski Destrianto",
      "category": "Project Collaborators",
      "affiliation": "Politeknik Negeri Semarang",
      "image": "https://media.licdn.com/dms/image/v2/C4E03AQH6wcJxldr2DA/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1605834017658?e=1755129600&v=beta&t=TzOoZSbcdKVa6VKANvzM-yNqsGKBCa0Xn2yW-RrJ8DM"
    },
    {
      "title": "Aishamanda Maretya Widyadhana",
      "category": "Project Collaborators",
      "affiliation": "Universitas Indonesia",
      "image": "https://media.licdn.com/dms/image/v2/D5603AQHJI1371IWRcA/profile-displayphoto-shrink_200_200/B56ZSM43K0GQAY-/0/1737530504525?e=1755129600&v=beta&t=EkSM9v25WVAvKPEVTdpvorjCQXCF0pbFSAK12zWIvp8"
    },
    {
      "title": "Azellia Anggun Viedyarani",
      "category": "Project Collaborators",
      "affiliation": "Universitas Brawijaya",
      "image": "https://media.licdn.com/dms/image/v2/D5603AQGMdTano45z3Q/profile-displayphoto-shrink_200_200/B56ZZR4ffcGcAY-/0/1745130487961?e=1755129600&v=beta&t=aPDjj4zLaqmU9K9u5UEt9GEA9qocjzuGi3455h-cKTw"
    },
    {
      "title": "Dimas Saputra",
      "category": "Project Collaborators",
      "affiliation": "Universitas Pendidikan Indonesia",
      "image": "https://media.licdn.com/dms/image/v2/D5603AQGD3ZBTmW0AMg/profile-displayphoto-shrink_200_200/B56ZNpFkjpGcAY-/0/1732634889846?e=1755129600&v=beta&t=wq2Q18KlIxI8XQT2y2-ffkyujnFkM3CRF09TaCYCVAo"
    },
    {
      "title": "Yasmin Ananda Putri",
      "category": "Project Collaborators",
      "affiliation": "Universitas Airlangga",
      "image": "https://media.licdn.com/dms/image/v2/D5603AQGO7T9IVyf3SQ/profile-displayphoto-shrink_200_200/B56ZdXw7S.HoAY-/0/1749524133502?e=1755129600&v=beta&t=2xS4yxgKbHLJAXP3coPeNwZXEVxWYFPGpJGorVx4XfQ"
    },
    {
      "title": "Barbara S. Lancho Barrantes",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "https://media.licdn.com/dms/image/v2/C4E03AQGcD_OLGstapg/profile-displayphoto-shrink_400_400/profile-displayphoto-shrink_400_400/0/1610979402338?e=1755129600&v=beta&t=7NmTSHm31BycjR2PJET4mUw3fIWk1BjM3tDpIT8jXqA"
    },
    {
      "title": "Savira Arumdini",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "https://media.licdn.com/dms/image/v2/D4D03AQHgfVdn6K0cZg/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1709738152095?e=1755129600&v=beta&t=p1rNzzJPqs48dRBLMXdXmJl8TCs3ajgEht42Ut97HOw"
    },
    {
      "title": "Ria Ariani",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "https://media.licdn.com/dms/image/v2/D5603AQELKfrcIiGY8A/profile-displayphoto-shrink_200_200/profile-displayphoto-shrink_200_200/0/1697511276801?e=1755129600&v=beta&t=qen-Z2CIveS6YB4q5znOtfJd02lPnCgAly_WUo4owq0"
    },
    {
      "title": "Noorika Retno Widuri",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "https://upload.wikimedia.org/wikipedia/commons/3/34/PICA.jpg"
    },
    {
      "title": "Dedi Suprianto",
      "category": "Academic Co-authors",
      "affiliation": "University of Brighton",
      "image": "https://upload.wikimedia.org/wikipedia/commons/3/34/PICA.jpg"
    }
  ] 
%}

<div class="projects">
{% for category in page.display_categories %}
  <a id="{{ category }}" href=".#{{ category }}">
    <h2 class="category text-capitalize">{{ category }}</h2>
  </a>
  {% assign filtered = projects | where: "category", category %}
  <div class="row row-cols-1 row-cols-md-5 g-4">
    {% for person in filtered %}
    <div class="col">
      <div class="card h-100">
        <img src="{{ person.image }}" class="card-img-top" alt="{{ person.title }}" style="object-fit: cover; height: 100px;">
        <div class="card-body text-center">
          <h5 class="card-title">{{ person.title }}</h5>
          <p class="card-text text-muted">{{ person.affiliation }}</p>
        </div>
      </div>
    </div>
    {% endfor %}
  </div>
{% endfor %}
</div>