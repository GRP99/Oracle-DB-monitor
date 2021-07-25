# Oracle-DB-monitor
## Database Administration and Exploration

### Contextualization
Using the knowledge acquired in the practical and theoretical component of the curricular unit of Administration and Database Exploration, the group built a DB monitor that presents, in a simple way, the main performance evaluation parameters of an Oracle DB.

### Topics
1. Creation of an [agent java](Agente/) that through the administration views performs the collection of information
necessary considered necessary.
2. Creation of a new [PDB](criacao_PDB-Schema-Tablespaces-Datafiles.txt), respective schema with permanent and temporary tablespaces and associated datafiles, in order to store the data collected in point 1. The collected data structure was modeled and presented in a [relational data model]((schema_database.sql)). The data model created includes the history of records. For example the evolution of the size (free space, occupied space) of a tablespace over time, or the number of sessions over time as well. The Enterprise Manager Console was considered to serve as an example.
3. Creation of a [REST API](dbmonitor/api/) that connects to the PBD created in point 2 and returns the results in the required JSON format. All endpoints created were documented.
4. Creation of a [web interface](dbmonitor/interface/) that presents the data collected in point 3.

### Team
![Gonçalo Pinto][grp-pic] | ![Nuno Costa][nuno-pic] | ![João Diogo Mota][joao-pic] | ![José Gonçalo Costa][goncalo-pic]
:---: | :---: | :---: | :---:
[Gonçalo Pinto][grp] | [Nuno Costa][nuno] | [João Diogo Mota][joao] | [José Gonçalo Costa][goncalo]

[grp]: https://github.com/GRP99
[grp-pic]: https://github.com/GRP99.png?size=120
[nuno]: https://github.com/jnuno420
[nuno-pic]: https://github.com/jnuno420.png?size=120
[joao]: https://github.com/JoaoDiogoMota
[joao-pic]: https://github.com/JoaoDiogoMota.png?size=120
[goncalo]: https://github.com/JoseCosta28
[goncalo-pic]: https://github.com/JoseCosta28.png?size=120

<div align="center">
  <sub>September 2020 - January 2021</sub>
</div>