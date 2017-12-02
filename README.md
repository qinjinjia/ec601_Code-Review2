# EC601_Code Review 2:mag:
## Brief Introduction :sunglasses:
  Hello Everyone! :trollface::trollface::trollface::trollface:
  
  This is the page for **EC601(Fall 2017) A1 Code Review 2 Assignment** :loop:
  
  The page for **EC601(Fall 2017) A1 Code Review 1 Assignment** can be found [HERE](https://github.com/qinjinjia/ec601_Code-Review) :loop:
  
  The **Code Review 2** follows the **same criteria** as the [Code Review 1](https://github.com/qinjinjia/ec601_Code-Review) . 
  
  |The project reviewed| **[@github.com/kev5/Go-Meet](https://github.com/kev5/Go-Meet)**
  |--|--
  |**The Reviewer**| :boy: **Qinjin Jia** qjia@bu.edu   :point_right:[@github/qinjinjia](https://github.com/qinjinjia)
  |**Criteria Followed**| [MIT 6.005 fall 15 - Reading 4 Code Review](http://web.mit.edu/6.005/www/fa15/classes/04-code-review/) 
  ||[Code Review Checklist](http://www.evoketechnologies.com/blog/code-review-checklist-perform-effective-code-reviews/)

  :sun_with_face: Summary of the Code Review Criteria :link: [Code Review Criteria.pdf](https://github.com/qinjinjia/ec601_Code-Review/blob/master/Code%20Review%20Criteria.pdf) 
 
 :full_moon_with_face: Code Review auxiliary tool: [jslint](http://www.jslint.com), [pep8](https://www.python.org/dev/peps/pep-0008/), [pylint](https://www.pylint.org)
 
## Overall
 :new_moon_with_face: This is an exciting project **[Go & Meet](https://github.com/kev5/Go-Meet)**. The project is essentially a **social/recreational application** which gives information of all the events  (public/private) happening in the local vicinity of the user on a real-time basis.
 
 :new_moon: The Github Repository of the Project **[Go & Meet](https://github.com/kev5/Go-Meet)** becomes more abundant. There are some new files:file_folder: are added into the repository. 
 
 :waxing_crescent_moon: **There is a ReadMe file in the repository, which is perfect**. However, there are many files in the Repository and **GitHub file structure and directory structure is not clearly understandable**. It seems that it is because the project is still under development :construction:. 

 :first_quarter_moon: There are ten java files I reviewed in **Code Review 1**:
          
 |File Name |Link |
 |--|--
 |ChooseLoginRegistrationActivity.java|:link: [ChooseLoginRegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/ChooseLoginRegistrationActivity.java)|
 |Community.java|:link: [Community.java](https://github.com/kev5/Go-Meet/blob/master/Community.java)|
 |Database.java|:link: [Database.java](https://github.com/kev5/Go-Meet/blob/master/Database.java)|
 |LoginActivity.java|:link: [LoginActivity.java](https://github.com/kev5/Go-Meet/blob/master/LoginActivity.java)|
 |MainActivity.java|:link: [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java)|
 |Post.java|:link: [Post.java](https://github.com/kev5/Go-Meet/blob/master/Post.java)|
 |RegistrationActivity.java|:link: [RegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/RegistrationActivity.java)|
 |User.java|:link: [User.java](https://github.com/kev5/Go-Meet/blob/master/User.java)|
 |readFromFireBase.java|:link: [readFromFireBase.java](https://github.com/kev5/Go-Meet/blob/master/readFromFireBase.java)|
 |writeToFireBase.java|:link: [writeToFireBase.java](https://github.com/kev5/Go-Meet/blob/master/writeToFireBase.java)|
 
 :waning_gibbous_moon: There are **five java files** and **four python files** I reviewed in **Code Review 2**:
 
 |File Name |Link |Comments|
 |--|--|--
 |ChooseLoginRegistrationActivity.java|:link: [ChooseLoginRegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/ChooseLoginRegistrationActivity.java)|Revised since Code Review 1|
 |Database.java|:link: [Database.java](https://github.com/kev5/Go-Meet/blob/master/Database.java)|Revised since Code Review 1|
 |LoginActivity.java|:link: [LoginActivity.java](https://github.com/kev5/Go-Meet/blob/master/LoginActivity.java)|Revised since Code Review 1|
 |MainActivity.java|:link: [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java)|Revised since Code Review 1|
 |RegistrationActivity.java|:link: [RegistrationActivity.java](https://github.com/kev5/Go-Meet/blob/master/RegistrationActivity.java)|Revised since Code Review 1|
 |boston_crime.py|:link: [boston_crime.py](https://github.com/kev5/Go-Meet/blob/master/boston_crime.py)|New Added|
 |csv2json.py|:link: [csv2json.py](https://github.com/kev5/Go-Meet/blob/master/csv2json.py)|New Added|
 |wikidata_get.py|:link: [wikidata_get.py](https://github.com/kev5/Go-Meet/blob/master/wikidata_get.py)|New Added|
 |zipcodeData.py|:link: [zipcodeData.py](https://github.com/kev5/Go-Meet/blob/master/zipcodeData.py)|New Added|
 |~~Community.java~~|:link: [~~Community.java~~](https://github.com/kev5/Go-Meet/blob/master/Community.java)|Removed before Code Review 2|
 |~~Post.java~~|:link: [~~Post.java~~](https://github.com/kev5/Go-Meet/blob/master/Post.java)|Removed before Code Review 2|
 |~~User.java~~|:link: [~~User.java~~](https://github.com/kev5/Go-Meet/blob/master/User.java)|Removed before Code Review 2|
 |~~readFromFireBase.java~~|:link: [~~readFromFireBase.java~~](https://github.com/kev5/Go-Meet/blob/master/readFromFireBase.java)|Removed before Code Review 2|
 
 
## Code Review2

### 1. Code Formatiing

All python files are assessed by the Code Review auxiliary tool: [pep8](https://www.python.org/dev/peps/pep-0008/) and [pylint](https://www.pylint.org) for an overview of the code quality.

 |Python File Name |Link |pep8 check |pylint check |
 |--|--|--|--
 |boston_crime.py|:link: [boston_crime.py](https://github.com/kev5/Go-Meet/blob/master/boston_crime.py)|25 Problems|4.59/10 |
 |csv2json.py|:link: [csv2json.py](https://github.com/kev5/Go-Meet/blob/master/csv2json.py)|7 Problems|3.75/10 |
 |wikidata_get.py|:link: [wikidata_get.py](https://github.com/kev5/Go-Meet/blob/master/wikidata_get.py)|9 Problems|-3.16/10 |
 |zipcodeData.py|:link: [zipcodeData.py](https://github.com/kev5/Go-Meet/blob/master/zipcodeData.py)|5 Problem|3.16/10 |
 
PEP8 Example: **PEP8 check for boston_crime.py**
```
boston_crime.py:9:43: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:9:45: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:17:80: E501 line too long (96 > 79 characters)
boston_crime.py:20:20: E261 at least two spaces before inline comment
boston_crime.py:20:20: E262 inline comment should start with '# '
boston_crime.py:25:1: E302 expected 2 blank lines, found 1
boston_crime.py:30:12: E231 missing whitespace after ','
boston_crime.py:32:13: E201 whitespace after '('
boston_crime.py:32:31: E202 whitespace before ')'
boston_crime.py:33:20: E221 multiple spaces before operator
boston_crime.py:36:1: W293 blank line contains whitespace
boston_crime.py:47:21: W291 trailing whitespace
boston_crime.py:48:38: E231 missing whitespace after ','
boston_crime.py:69:12: E231 missing whitespace after ','
boston_crime.py:72:14: W291 trailing whitespace
boston_crime.py:76:70: W291 trailing whitespace
boston_crime.py:79:14: W291 trailing whitespace
boston_crime.py:86:80: E501 line too long (259 > 79 characters)
boston_crime.py:88:1: W293 blank line contains whitespace
boston_crime.py:89:1: W293 blank line contains whitespace
boston_crime.py:91:43: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:91:45: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:92:60: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:92:62: E251 unexpected spaces around keyword / parameter equals
boston_crime.py:92:76: W292 no newline at end of file
```

Pylint Example: **Pylint check for boston_crime.py**
```
************* Module boston_crime
C:  9, 0: No space allowed around keyword argument assignment
f3 = open("zip_pos_us.csv", 'rt', encoding = 'latin-1')
                                           ^ (bad-whitespace)
C: 30, 0: Exactly one space required after comma
    for key,value in zip_boston_pos.items():
           ^ (bad-whitespace)
C: 32, 0: Unnecessary parens after 'if' keyword (superfluous-parens)
C: 32, 0: No space allowed after bracket
        if ( distance < lenmin ):
           ^ (bad-whitespace)
C: 32, 0: No space allowed before bracket
        if ( distance < lenmin ):
                               ^ (bad-whitespace)
C: 33, 0: Exactly one space required before assignment
            zipcode  = key
                     ^ (bad-whitespace)
C: 36, 0: Trailing whitespace (trailing-whitespace)
C: 47, 0: Trailing whitespace (trailing-whitespace)
C: 48, 0: Unnecessary parens after 'in' keyword (superfluous-parens)
C: 48, 0: Exactly one space required after comma
        for key, value in (zip(header,row)):
                                     ^ (bad-whitespace)
W: 49, 0: Bad indentation. Found 16 spaces, expected 12 (bad-indentation)
C: 69, 0: Exactly one space required after comma
    for key,value in d.items():
           ^ (bad-whitespace)
C: 72, 0: Trailing whitespace (trailing-whitespace)
C: 76, 0: Trailing whitespace (trailing-whitespace)
C: 79, 0: Trailing whitespace (trailing-whitespace)
C: 86, 0: Line too long (259/100) (line-too-long)
C: 88, 0: Trailing whitespace (trailing-whitespace)
C: 89, 0: Trailing whitespace (trailing-whitespace)
C: 91, 0: No space allowed around keyword argument assignment
json.dumps(dict(boston_crime_data_from2015 = data))
                                           ^ (bad-whitespace)
C: 92, 0: Final newline missing (missing-final-newline)
C: 92, 0: No space allowed around keyword argument assignment
print(json.dumps(dict(boston_crime_data_from2015_statistics = crime_stat)))
                                                            ^ (bad-whitespace)
C:  1, 0: Missing module docstring (missing-docstring)
C:  5, 0: Invalid constant name "f1" (invalid-name)
C:  6, 0: Invalid constant name "reader1" (invalid-name)
C:  7, 0: Invalid constant name "f2" (invalid-name)
C:  8, 0: Invalid constant name "reader2" (invalid-name)
C:  9, 0: Invalid constant name "f3" (invalid-name)
C: 10, 0: Invalid constant name "reader3" (invalid-name)
C: 12, 0: Invalid constant name "zip_boston" (invalid-name)
C: 13, 0: Invalid constant name "zip_boston_pos" (invalid-name)
W: 29, 4: Redefining name 'zipcode' from outer scope (line 39) (redefined-outer-name)
W: 30, 8: Redefining name 'key' from outer scope (line 48) (redefined-outer-name)
W: 30,12: Redefining name 'value' from outer scope (line 48) (redefined-outer-name)
C: 25, 0: Missing function docstring (missing-docstring)
C: 37, 0: Invalid constant name "data" (invalid-name)
C: 38, 0: Invalid constant name "header" (invalid-name)
C: 39, 0: Invalid constant name "zipcode" (invalid-name)
C: 42, 7: Do not use `len(SEQUENCE)` as condition value (len-as-condition)
W: 46, 8: No exception type(s) specified (bare-except)
C: 58, 0: Invalid constant name "crime_stat" (invalid-name)

-----------------------------------
Your code has been rated at 4.59/10
```
According to the **Code Review auxiliary tool Pep8 and Pylint, Overall Code Quality(Formatting) is OK.**

#### 1.1 Alignments
For all java files revised after Code Review 1 and all new added python files, the uses of alignments are perfect. The code block starting point and ending point are **easily identifiable**.

#### 1.2 Naming Conventions
The **‘camelCode’** nameing convention is used in the project. The developers utilize capital letters to indicate the start of a word, which makes name of variables be **meaningful**.

#### 1.3 Code Layout
:thumbsup:Perfect! The code can fit in the standard 14-inch laptop screen.

#### 1.4 Commented Code

The commented code in [Database.java](https://github.com/kev5/Go-Meet/blob/master/Database.java) has been deleted (Or removed from the master branch) before Code Review 2.   
```
public class Database {
    public FirebaseDatabase mDatabase;
    public DatabaseReference myRef;
//    public String ID = "690";                <-This commented code should be removed
    public Database(){
    }
```
and the commented code in [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java) has been removed as well.
```
        al.add(post01.getPostText());
//        al.add(post02.getPostText());        <-This commented code should be removed
//        al.add(post03.getPostText());
//        al.add(post04.getPostText());
//        al.add(post05.getPostText());
//        al.add(post06.getPostText());
```
However, it seems that it is because the project is still under development :construction:. There are still some commented code blocks in the project.
The commented code in [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java), for instance.
```
//    public void postEvent(View view) {
//        view = (LayoutInflater.from(MainActivity.this)).inflate(R.layout.activity_post, null);
//        AlertDialog.Builder alertBuilder = new AlertDialog.Builder(MainActivity.this);
//        alertBuilder.setView(view);
//
//        Dialog dialog = alertBuilder.create();
//        dialog.show();
//
//        alertBuilder.setCancelable(true)
//                .setPositiveButton("GO", new DialogInterface.OnClickListener(){
//                    //private EditText mEventName;
//
//                    @Override
//                    public void onClick(DialogInterface dialog,int which){
//                        mEventName = (EditText) findViewById(R.id.event_name);
//                        final String eventName = mEventName.getText().toString();
//                        final String userId = mAuth.getCurrentUser().getUid();
//                        DatabaseReference postDb = FirebaseDatabase.getInstance().getReference().child("Users").child(userSex).child(userId).child("dd");
//                        postDb.setValue(eventName);
//
//                    }
//                });
//    }
```

</br>

### 2. Architecture

It seems that the developers follow the [Singleton pattern](https://en.wikipedia.org/wiki/Singleton_pattern), which is good. 

Additionally, code is in sync with existing code patterns/technologies.

Therefore, the architecture of the project is nice.

</br>

### 3. Coding best practices

#### 3.1 Hard Coding
:thumbsup: Good!. There is no [hard coding](https://en.wikipedia.org/wiki/Hard_coding) in the project.

#### 3.2 Enumeration
The java file :link: [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java) contains **[magic number](https://en.wikipedia.org/wiki/Magic_number_(programming))**. It is difficult to understand what is the meaning of 1, 2, 3 etc here.
This might be solved by utilizing the enumeration.
```
        mWrite.writePosts("1",post01);
        mWrite.writePosts("2",post02);
        mWrite.writePosts("3",post03);
        mWrite.writePosts("4",post04);
        mWrite.writePosts("5",post05);
        mWrite.writePosts("6",post06);
```
**This issue has been revised before the Code Review 2.** :thumbsup: **Perfect!**

#### 3.3 Comments
There are some to-do comments mention pending tasks, which is good. For instance, in [User.java](https://github.com/kev5/Go-Meet/blob/master/User.java)
```
    public User() {
        // Default constructor required for calls to DataSnapshot.getValue(User.class)
    }
```

However, this kind of comments(i.e. comments to help developer understand the tutorial) should be deleted (or removed from the master branch).
```
    public void onLeftCardExit(Object dataObject) {
        //Do something on the left!
        //You also have access to the original object.
        //If you want to use it just cast it (String) dataObject
        Toast.makeText(MainActivity.this, "NOPE!", Toast.LENGTH_SHORT).show();
    }
```
Additionally, the developers could add some comments to help others understand the code.

#### 3.4 Mul if/else blocks
:thumbsup: Good, there is no multiple if/else block in the project.

#### 3.5 Framework features
N/A

</br>

### 4. Non Functional requirements
#### 4.1 Maintainability(Supportability) 
The **Readability** of the code is good. The team uses **‘camelCode’ nameing convention**, which makes name of variables be meaningful.
The project is still under development :construction:, there is **no .apk file in the repository**, therefore, **"Testability", "Debuggability", "Configurability"** of the project are not reviewed. Unit test should not start until the project finished.


#### 4.2 Reusability
Some places in the code violate [DRY (Do not Repeat Yourself) principle](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself).Duplicated code is a risk to safety. If you have identical or very similar code in two places, then the fundamental risk is that there’s a bug in both copies, and some maintainer fixes the bug in one place but not the other. For instance, **DRY code** in :link: [writeToFireBase.java](https://github.com/kev5/Go-Meet/blob/master/writeToFireBase.java)
```
    public void likePost(String postID){
        DatabaseReference commentPostRef = this.writepostRef.child(postID);
        commentPostRef.child("likes").push().setValue(this.user.getUid());
    }

    public void dislikePost(String postID){
        DatabaseReference commentPostRef = this.writepostRef.child(postID);
        commentPostRef.child("dislikes").push().setValue(this.user.getUid());
    }
```

However, the project utilizes **generic functions and classes**, which increase reusability of the project. 

#### 4.3 Reliability:
Exception handling is not found in the code, which could be considered to add after achieveing the main functions of the software.

#### 4.4 Extensibility
The project utilizes classes and functions, which makes the code has **Good Extensibility**. The enhancements could be added to the existing code with minimal changes under this design(i.e. classes and functions).

#### 4.5 Security
The developers considered the security of the software, **Authentication is addded by utilizing the firebase** in [LoginActivity.java](https://github.com/kev5/Go-Meet/blob/master/LoginActivity.java).
```
        public void onClick(View v) {
                final String email = mEmail.getText().toString();
                final String password = mPassword.getText().toString();
```               

#### 4.6 Performance
The project is still under development :construction:, there is **no .apk file in the repository**, therefore, **Performance** of the project is not reviewed.

#### 4.7 Scalability
The **firebase realtime database** is utilized as the backend of the porject, which can be found in [writeToFireBase.java](https://github.com/kev5/Go-Meet/blob/master/writeToFireBase.java).  **The firebase realtime database** supports a large user base/data. Therefore, the scalability of the project is good.
```
    public writeToFireBase(){
        this.user = FirebaseAuth.getInstance().getCurrentUser();
        this.database = FirebaseDatabase.getInstance();
        this.writepostRef = this.database.getReference("posts");
        this.userRef = this.database.getReference("users");
    }
```

#### 4.8 Usability
The project is still under development :construction:, therefore, **Usability** of the project is not reviewed.

</br>

### 5. Object-Oriented Analysis and Design (OOAD) Principles

#### 5.1 Single Responsibility Principle(SRS)
The classes in the code are checked, each single class or function has one responsibility. Therefore, **the code obeys the Single Responsibility Principle (SRS)**. Nice design! :clap:

#### 5.2 Open Closed Principle
Owing to the developers' good design, each single class or function has one responsibility. While adding new functionality, existing code does not need to be modified. Therefore, the project obeys the **Open Closed Principle**.

#### 5.3 Liskov substitutability principle 
The class hierarchy does not exist in the project. Therefore, the project does not violate the **[Liskov substitutability principle]**(https://en.wikipedia.org/wiki/Liskov_substitution_principle)

#### 5.4 Interface segregation:
The project is still under development :construction:, there is **no .apk file in the repository**, therefore, **Interface segregation** of the project is not reviewed.

#### 5.5 Dependency Injection:
The project utilizes **firebase** to achieve authentication. Dependency injection is not applicable to the project.

## Summary

### Good Points: 
:full_moon_with_face: The overall code quality is high, the design of the software is good. Many issues mentioned in [Code Review 1](https://github.com/qinjinjia/ec601_Code-Review) has been revised. Commented Code Problem, for instance. Thanks :tada:.

:new_moon_with_face: The project has **proper code formatiing**，using **‘camelCode’ nameing convention** makes name of variables be **meaningful**. However, code formatting still can be improved according to the reports from the Code Review auxiliary tool: [jslint](http://www.jslint.com), [pep8](https://www.python.org/dev/peps/pep-0008/), [pylint](https://www.pylint.org). 

:new_moon: The architecture of the project is nice.

:waxing_crescent_moon: There are some **to-do comments** mention pending tasks, which is good.

:first_quarter_moon: The **Readability** of the code is good. The developers considered the security of the software, **Authentication is addded by utilizing the firebase**.

:waxing_gibbous_moon: The project obeys **Single Responsibility Principle(SRS)**, **Open Closed Principle** and **Liskov substitutability principle**. 

### Can be better:
:full_moon: **GitHub file structure and directory structure is not clearly understandable**. It seems that it is because the project is still under development :construction:.

:waning_gibbous_moon:There are some **commented code blocks** in the project. The commented code blocks could keep in other branch rather than the master branch.

:last_quarter_moon: The developers could add **some comments to help others understand the code**.

:waning_crescent_moon: The java file :link: [MainActivity.java](https://github.com/kev5/Go-Meet/blob/master/MainActivity.java) contains **[magic number](https://en.wikipedia.org/wiki/Magic_number_(programming))**.


:sun_with_face: **Finally, Good Luck for your project :D)**:exclamation:

:trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface::trollface:
