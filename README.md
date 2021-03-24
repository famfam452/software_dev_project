# API DOCS 

## LIST OF API 

- User Information 
- Course Information 
- Curriculum Information 
- Faculty Information 
- Major Information 

# User Information 

## ENDPOINT       
    GET /User/{Student_ID} 

## Prerequisite 
- None 

## Request :  
    { 
        " Student_ID ": "60010105", 
    } 

## Response:  
    { 

        "Student_ID ": "60010105", 

        "Name": "Khajohnyos Boonkate", 

        "Email":"60010105@kmitl.ac.th", 

        "Student_Year":"4", 

        "Department_ID":"04", 

        "Major_ID":"02", 

        "Faculty_ID":"01", 

    } 


# Course Information (รายวิชา) 

## ENDPOINT    

    GET : /Course/{Course_ID}/ 

Prerequisite 
- None 

Request :  
{ 
	"Course_ID": "01236152", 
} 

Response:  
{ 

    "ID":"01236152", 

    "Title":"Software Development", 

    "Credit":"3", 

    "Description":"Fun Course", 

    "Category_ID":"02", 

    "Group_ID":"04", 

    "Type":"Credit", 

    "Prerequisite":"None" 

  } 
Curriculum Information (หลักสูตร) 

ENDPOINT       
GET : /Curriculum/{Curriculum_ID}/ 

Prerequisite 
None 

Request :  
{ 
	" Curriculum_ID ": "25600291", 
} 

Response:  
{ 

    "ID":"10245", 

    "Title":{ 

        "thai":"หลักสูตรวิศวกรรมศาสตรบัณฑิต สาขาวิชาวิศวกรรมสารสนเทศ", 

        "eng":"Bachelor of Engineering Program in Information Engineering" 

    }, 

    "Degree_Title":{ 

        "full_name":{ 

            "thai":"วิศวกรรมศาสตรบัณฑิต (วิศวกรรมสารสนเทศ)", 

            "eng":"Bachelor of Engineering (Information Engineering)" 

        }, 

        "short_name":{ 

            "thai":"วศ.บ. (วิศวกรรมสารสนเทศ)", 

            "eng":"B.Eng. (Information Engineering)" 

        } 

    }, 

    "Revision":"60", 

    "Faculty_ID":"01", 

    "Program_Type":{ 

        "Study_Years":"4", 

        "type":"หลักสูตรปรญญาตรีทางวิชาการ", 

        "laguages":"หลักสูตรจัดการศึกษาเป็นภาษาไทย/ภาษาอังกฤษ", 

        "in_condition":"รับทั้งนักศึกษาไทยและนักศึกษาต่างชาติที่ใช้ภาษาไทยได้ดี", 

        "MOU":"เป็นหลักสูตรของสถาบันโดยเฉพาะ", 

        "out_condition":"ให้ปริญญาเพียงสาขาวิชาเดียว" 

    }, 

    "Structure_Curriculum":{ 

        "total_credit":"138", 

        "structure":{ 

            "genend":{ 

                "กลุ่มคุณค่าแห่งชีวิต": "6", 

                "กลุ่มวิถีแห่งสังคม": "3", 

                "กลุ่มศาสตร์แห่งความคิด": "3", 

                "กลุ่มศิลปะแห่งการจัดการ": "3", 

                "กลุ่มภาษาและการสื่อสาร": "12", 

                "วิชาเลือก (เลือกจากทั้ง 5 กลุ่ม)": "3" 

            }, 

            "specific":{ 

                "กลุ่มวิชาวิศวกรรมพื้นฐาน":"20", 

                "กลุ่มวิชาวิศวกรรมสารสนเทศพื้นฐาน": "64", 

                "กลุ่มวิชาการศึกษาทางเลือก":"6", 

                "กลุ่มวิชาเลือกเฉพาะสาขา":"12" 

            }, 

            "free":"6" 

        } 

    }, 

    "List_of_subjects": [ 
        { 

            "years":"1", 

            "semester": "1", 

            "subjects": [ 

                { 

                    "id": "01006030", 

                    "title": "Cal", 

                    "credit": "(3-0-6)" 

                } 

            ] 

        }, 

    ] 

 

 

 

} 

 

Faculty Information  

ENDPOINT       
GET : /Faculty/{Faculty_ID}/ 

Prerequisite 
- None 

Request :  
{ 
	"Faculty_ID": "01", 
} 

Response:  
{ 

       "ID":"01", 

       "Title":"Engineering" 

  } 

Major Information 

ENDPOINT       
GET : /Major/{Major_ID}/ 

Prerequisite 
- None 

Request :  
{ 
	"Major_ID": "01", 
} 

Response:  
{ 

       "ID":"02", 

       "Title":"Information Engineering" 

 } 

 

 

 

 

 

 

 

 

 

 

 
 

 