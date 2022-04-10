# Lesson_11_Intro_to_OOP
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Lesson_11_OOP
{
    public class schoolSystem
    {
        string _name;
        
        string teacher;
        string location;
        public schoolSystem()
        {
            _name = "KST";
        }

        public schoolSystem(string name)
        {
            _name = name;
        }

        public void montessori()
        {
            Console.WriteLine();
        }
        public void military()
        {
            Console.WriteLine();
        }
        

        public string student
        {
            get { return student; }
            set { student = value; }
        }

    }
    
}

//Exercise 2
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Lesson_11_OOP
{
    public abstract class Mobilephone
    {
        public abstract void calling();
        public abstract void textmessage();
    }
    public class Mobilephone1 : Mobilephone
    {
        public override void calling()
        {
            throw new NotImplementedException();
        }

        public override void textmessage()
        {
            throw new NotImplementedException();
        }
        public  void video()
        {

        }
        public void mms()
        {

        }
        public void camera()
        {

        }
    }

    public class Mobilephone2 : Mobilephone
    {
        public override void calling()
        {
            throw new NotImplementedException();
        }

        public override void textmessage()
        {
            throw new NotImplementedException();
        }

        public void video()
        {

        }
        public void mms()
        {

        }
        public void camera()
        {

        }

        public void email()
        {

        }
        public void games()
        {

        }
        public void messaging()
        {

        }
    }
}
