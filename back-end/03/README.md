### 学校管理系统
* 使用原生PHP+mysql实现一个学校管理系统，页面UI不需要考虑，包含的功能页面大概如效果图1图片所示
* 包含的数据表有：hy_student（学生表），字段：student_no（学号，类型varchar50），name（学生姓名，类型varchar50），sex（性别，类型tinyint1），class_no（所在班级编号，类型varchar10）
* hy_class（班级表），字段：class_no（班级编号，类型varchar10），class_name（班级名称，类型varchar20），department（院系名称，varchar30），grade（年级，类型int5）
* hy_course（课程表），字段：course_no（课程编号，类型varchar10），course_name（课程名称，类型varchar20），credit（学分，类型int5），hours（学时数，类型int2），term（开课学期，类型varchar2）
* hy_score（成绩表），字段：student_no（学号，类型varchar50），course_no（课程编号，类型varchar10），score（成绩，int3）