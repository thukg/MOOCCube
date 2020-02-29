# MOOCCube

Download link: [MOOCCube](http://lfs.aminer.cn/misc/moocdata/data/mooc_cube.zip)

## Entities

MOOCCube dataset contains these types of entities:

| type     | prefix of id |
| -------- | ------------ |
| concept  | K_           |
| course   | C_           |
| paper    | P_           |
| school   | S_           |
| teacher  | T_           |
| user     | U_           |
| video    | V_           |
| taxonomy | K_T_         |

Each line is a JSON object.

## Relations

- concept-field
- concept-paper
- course-concept
- course-video
- parent-son (taxonomy)
- prerequisite-dependency
- school-course
- school-teacher
- teacher-course
- user-course
- user-video
- video-concept

Each line contains two entities separated by '\t'.

## Additional information

concept-information: more text data of each concept.

course-concept, video-concept: each line is a JSON object which represents a course / video and its merged concept relations.

user_video_act: filtered watching video behavior of users.

