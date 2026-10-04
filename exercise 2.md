<?xml version= "1.0" encoding "UTF"-8?>   
<!ELEMENT course-list(title,description+,credits,prerequsities,semester)>  
<!ELEMENT title (#PCDATA)>  
<!ELEMENT description (focus,skills)>  
<!ELEMENT credits (#PCDATA)>  
<!ELEMENT prerequisites(#PCDATA)>  
<!ELEMENT semester (#PCDATA)>

<?xml version= "1.0" encoding "UTF"-8?>   
<!DOCTYPE Course list "course.dtd">  
<?xml-stylesheet type= "text/css” href= "course.css”>  
<course-list>   
  <title> ENG 362- Buisness and Professional Writing <title\>  
  <description>  
    <focus> A Writing Intensive course focused on practice with professional documents including hiring materials, proposals, evaluations, and memos.<focus\>  
    <skills> Particular emphasis is placed on collaborative writing, editing, and project-based writing.<skills\>  
  <credits> Credits:3 <credits\>  
  <prerequisites>Required Prerequisites: ENG 111 <prerequisites\>  
  <semester> Semester Offfered: Fall, Spring <semester\>  
<course-list\>

title {  
 font-weight: bold  
 color: black;  
 text-align: left;  
}  
description {  
 color: gray;  
 text-align: left;  
}  
prerequisites {  
 font-weight: bold;  
}
