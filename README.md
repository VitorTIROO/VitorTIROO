### Hi there, I'm Vitor! 👋

# Welcome!

  ![Most Used Language](https://github-readme-stats.vercel.app/api/top-langs/?username=VitorTIROO&theme=dark&show_icons=true) 
  
:computer: I'm Back-End Developer!

:house_with_garden: I’m from Brazil.

:books: I’m currently learning everything.
 

## About me

[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/VitorTIROO)](https://github.com/VitorTIROO)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/vitor-santos-4105b4a1)](https://www.linkedin.com/in/vitor-santos-4105b4a1) [<img src="https://www.sankhya.com.br/wp-content/uploads/2021/02/Sankhya_site_favicon_32x32.png" alt="Comunidade Sankhya" width="34">](https://comunidade.sankhya.com.br/u/vitor_santos)

- Thanks for visiting.

- Enjoy it!! o/
```java
                DynamicVO histNewVO = (DynamicVO) dwfEntityFacade.getDefaultValueObjectInstance("AD_TCFHISTGR");
                histNewVO.setProperty("GR", "GR");
                histNewVO.setProperty("CODVEICULO", veiculoVO.asBigDecimal("CODVEICULO"));
                histNewVO.setProperty("CODVEI1", veiculoVO.asBigDecimal("AD_CODVEI1"));
                histNewVO.setProperty("CODVEI2", veiculoVO.asBigDecimal("AD_CODVEI2"));
                histNewVO.setProperty("CODVEI3", veiculoVO.asBigDecimal("AD_CODVEI3"));
                histNewVO.setProperty("CODPARCMOTORISTA", motoristaVO.asBigDecimal("CODPARC"));
                histNewVO.setProperty("CODPARCPROP", proprietario.asBigDecimal("CODPARC"));
                histNewVO.setProperty("CODPARCPROPCAR1", (carreta1VO == null ? null : carreta1VO.asBigDecimal("CODPARC")));
                histNewVO.setProperty("CODPARCPROPCAR2", (carreta2VO == null ? null : carreta2VO.asBigDecimal("CODPARC")));
                histNewVO.setProperty("CODPARCPROPCAR3", (carreta3VO == null ? null : carreta3VO.asBigDecimal("CODPARC")));
                histNewVO.setProperty("PROTOCOLO", "");
                histNewVO.setProperty("ID", id);
                histNewVO.setProperty("CODUSU", this.contexto.getUsuarioLogado());
                histNewVO.setProperty("DHSOLICITACAO", TimeUtils.getNow());
                histNewVO.setProperty("TIPOANALISE", usaPesquisaAvancada ? "A" : "S");
                histNewVO.setProperty("CHECKLISTVEI", realizaInspecao ? "E" : "N");
                histNewVO.setProperty("STATUSPROCESSO", status);
                histNewVO.setProperty("STATUSANALISE", status);
                histNewVO.setProperty("DTVALIDADE", null);
                histNewVO.setProperty("RESPONSE", (solicitante + "\n" + gson.toJson(retorno)).toCharArray());
                dwfEntityFacade.createEntity("AD_TCFHISTGR", (EntityVO) histNewVO);
```
<!--
**VitorTIROO/VitorTIROO** is a ✨
 _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
