## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/muchen1224/muchen1224.github.io/edit/master/index.md) to maintain and preview the content for your website in Markdown files.
我感觉你在无中生有，胡言乱语，无可救药。。。
Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 

#include<stdlib.h>
//存储名和姓
struct name
{
   char xing[30];
   char ming[30];
};
//三个成员 name结构  grade数组
struct student          
{       
    struct name names;
    double grade[3];
    double average;
    
};
#define CSIZE 4
int main(void)
{
    struct student students[CSIZE];
    //d
    for(int i = 0;i <CSIZE;i++)
    {
        printf("please you enter xing:");
        fgets(students[i].names.xing,30,stdin);
        printf("please enter ming:");
        fgets(students[i].names.ming,30,stdin);
        printf("Enter three grades of this student: ");
       
        for(int j = 0;j < CSIZE ; j++)
        {
            scanf("%1f",&students[i].grade[j]);
            getchar() != '\n';
        }
        
     }
        //e
         for (int i = 0; i < CSIZE; i++)
    {
        double total_grade = 0.0;
        for (int j = 0; j < 3; j++)
        {
            total_grade += students[i].grade[j];
        }
        students[i].average = total_grade / 3;
    }
    //f
     for (int i = 0; i < CSIZE; i++)
    {
        printf("Student: %s, %s, grade: %.2lf, %.2lf, %.2lf, average: %.2lf\n", students[i].names.xing, students[i].names.ming,
            students[i].grade[0], students[i].grade[1], students[i].grade[2], students[i].average);
    }
    // g
    double total_grades = 0.0;
    for (int i = 0; i < CSIZE; i++)
    {
        total_grades += students[i].average;
    }
    printf("All students' average grade is %.2lf\n", total_grades / CSIZE);
    system("pause");
    return 0;
   
    *//任海宁，肖美
}

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/muchen1224/muchen1224.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
