- 👋 Hi, I’m @Ricardobolt
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Ricardobolt/Ricardobolt is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace Urna eletronica 1projeto!
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "1";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "1";
            }
        }

        private void button4_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "4";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "4";
            }
        }

        private void richTextBox2_TextChanged(object sender, EventArgs e)
        {

        }

        private void textBox1_TextChanged(object sender, EventArgs e)
        {

        }

        private void label1_Click(object sender, EventArgs e)
        {

        }

        private void button0_Click(object sender, EventArgs e)
        {
            string voto;
            if (tbcx1.Text == "")
            {
                tbcx1.Text = "0";
            }
            else
                if (tbcx2.Text == "")
                    {
                       tbcx2.Text = "0";
                       voto = tbcx1.Text + tbcx2.Text;
                       if (voto == "10")
                       {
                            lblnome.Text = "Candidado 10";
                       }
                       else if (voto == "11")
                {
                    lblnome.Text = "Candidado 11";
                }
            }
                

        }

        private void button2_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "2";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "2";
            }
        }

        private void button3_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "3";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "3";
            }
        }

        private void button5_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "5";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "5";
            }
        }

        private void button6_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "6";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "6";
            }
        }

        private void button7_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "7";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "7";
            }
        }

        private void button8_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "8";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "8";
            }
        }

        private void button9_Click(object sender, EventArgs e)
        {

            if (tbcx1.Text == "")
            {
                tbcx1.Text = "9";
            }
            else
                if (tbcx2.Text == "")
            {
                tbcx2.Text = "9";
            }
        }

        private void corrigir_Click(object sender, EventArgs e)
        {
            tbcx1.Text = "";
            tbcx2.Text = "";



        }

        private void branco_Click(object sender, EventArgs e)
        {
            tbcx1.Text = "0";
            tbcx2.Text = "0";
        }

        private void confirma_Click(object sender, EventArgs e)
        {
            //if voto == 10
            //   c10 = c10 + 1

        }
    }
