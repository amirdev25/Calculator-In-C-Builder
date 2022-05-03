//---------------------------------------------------------------------------
//       1-amal=bulish;
//       2-amal=kupaytirish;
//       3-amal=qo'shish;
//       4-amal=ayirish;
//       5-amal=daraja;
//       6-amal=foiz;
//       7-amal=ildiz;
//       8-amal=1/x;

#include <vcl.h>
#pragma hdrstop
#include<math.h>

#include "Unit1.h"
//---------------------------------------------------------------------------
#pragma package(smart_init)
#pragma link "sSkinManager"
#pragma link "sSkinManager"
#pragma link "sSkinManager"
#pragma link "sEdit"
#pragma link "sSkinManager"
#pragma resource "*.dfm"
TForm1 *Form1;
bool yangi=true;
double son1,son2;
int amal;
double natija;
double memory=0;
//---------------------------------------------------------------------------
__fastcall TForm1::TForm1(TComponent* Owner)
        : TForm(Owner)
{
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button2Click(TObject *Sender)
{
if(Label1->Caption.Length()<10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="0";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"0";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button5Click(TObject *Sender)
{
if(Label1->Caption.Length()<10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="1";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"1";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button23Click(TObject *Sender)
{
Label1->Caption="0";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button6Click(TObject *Sender)
{
if(Label1->Caption.Length()<10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="2";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"2";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button7Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="3";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"3";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button9Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="4";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"4";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button10Click(TObject *Sender)
{
 if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="5";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"5";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::FormCreate(TObject *Sender)
{
  if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="6";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"6";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button13Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="7";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"7";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button14Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="8";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"8";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button15Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="9";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"9";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button21Click(TObject *Sender)
{
if(Label1->Caption.Length()==1)
Label1->Caption="0";
else{
int uzn=Label1->Caption.Length();
Label1->Caption=Label1->Caption.Delete(uzn,1);
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button11Click(TObject *Sender)
{
if(Label1->Caption.Length()<=10){
if(yangi==True || Label1->Caption=="0"){
Label1->Caption="6";
yangi=False;
}
else{
Label1->Caption=Label1->Caption+"6";
}
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button4Click(TObject *Sender)
{
Label1->Caption="0";
Label2->Caption="";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button1Click(TObject *Sender)
{
int m=Label1->Caption.Pos(".");
if(m==0)
Label1->Caption=Label1->Caption+".";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button24Click(TObject *Sender)
{
amal=1;
son1=StrToFloat(Label1->Caption);
yangi= True;
Label2->Caption=FloatToStr(son1)+" / ";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button19Click(TObject *Sender)
{
amal=2;
son1=StrToFloat(Label1->Caption);
yangi= True;
Label2->Caption=FloatToStr(son1)+" * ";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button18Click(TObject *Sender)
{
amal=3;
son1=StrToFloat(Label1->Caption);
yangi= True;
Label2->Caption=FloatToStr(son1)+" + ";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button17Click(TObject *Sender)
{
amal=4;
son1=StrToFloat(Label1->Caption);
yangi= True;
Label2->Caption=FloatToStr(son1)+" - ";
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button12Click(TObject *Sender)
{
amal=6;
son1=StrToFloat(Label1->Caption);
Label2->Caption=Label1->Caption+" % ";
yangi = True;
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button3Click(TObject *Sender)
{
son2=StrToFloat(Label1->Caption);
if(amal==1){
if(son2==0)
ShowMessage("kechirasiz nolga bo'lish mumkin emas");
else{
natija=son1/son2;
String nat=FloatToStr(natija);
if(nat.Length()>10)
nat=nat.Delete(10,nat.Length());
Label2->Caption=Label2->Caption+FloatToStr(son2)+" = ";
Label1->Caption=nat;
yangi=True;
}
}
if(amal==2){
natija=son1*son2;
if(son2>999999999999999)
ShowMessage("ko'paytma juda katta");
else{
Label2->Caption=Label2->Caption+FloatToStr(son2)+" = ";
Label1->Caption=FloatToStr(natija);
yangi=True;
}
}
if(amal==3){
natija=son1+son2;
Label2->Caption=Label2->Caption+FloatToStr(son2)+" = ";
Label1->Caption=FloatToStr(natija);
yangi=True;
}
if(amal==4){
natija=son1-son2;
Label2->Caption=Label2->Caption+FloatToStr(son2)+" = ";
Label1->Caption=FloatToStr(natija);
yangi=True;
}
if(amal==6){
natija=(son1*son2)/100;
Label2->Caption=Label2->Caption+" ( " + Label1->Caption+" ) = ";
Label1->Caption=FloatToStr(natija);
yangi=True;
}
if(amal==5){
natija=1;
for(int i=0;i<son2;i++){
 natija*=son1;
 }
Label2->Caption=Label2->Caption+" ( "+Label1->Caption+" ) =";
Label1->Caption=FloatToStr(natija);
yangi=True;
}
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Label2Click(TObject *Sender)
{
ShowMessage(Label2->Caption);
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button16Click(TObject *Sender)
{
double man=StrToFloat(Label1->Caption);
Label1->Caption=FloatToStr(-1*man);
}
//---------------------------------------------------------------------------
void __fastcall TForm1::Button25Click(TObject *Sender)
{
amal=5;
son1=StrToFloat(Label1->Caption);
Label2->Caption=Label1->Caption+ " ^ ";
yangi=True;
}

//---------------------------------------------------------------------------

//---------------------------------------------------------------------------


void __fastcall TForm1::Button8Click(TObject *Sender)
{
amal=8;
son1=StrToFloat(Label1->Caption);
Label2->Caption="1 / "+Label1->Caption+" = ";
String satr=FloatToStr(1/son1);
if(satr.Length()>=10){
satr.Delete(10,satr.Length());
}
Label1->Caption=satr;
yangi=True;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button28Click(TObject *Sender)
{
Label3->Visible=True;
memory=memory+StrToFloat(Label1->Caption);
yangi=True;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button26Click(TObject *Sender)
{
Label3->Visible=False;
memory=0;
yangi=True;
Label1->Caption="";
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button27Click(TObject *Sender)
{
Label2->Caption="xotiradagi son";
Label3->Visible=True;
Label1->Caption=FloatToStr(memory);
yangi=True;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button29Click(TObject *Sender)
{
Label3->Visible=True;
memory=memory-StrToFloat(Label1->Caption);
yangi=True;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::Button30Click(TObject *Sender)
{
Label3->Visible=True;
memory=StrToFloat(Label1->Caption);
yangi=True;
}
//---------------------------------------------------------------------------



void __fastcall TForm1::Button20Click(TObject *Sender)
{
double sonn=StrToFloat(Label1->Caption);
String sonn1=FloatToStr(sqrt(sonn));
if(sonn1.Length()>10){
sonn1=sonn1.Delete(10,sonn1.Length()-10);
}


Label1->Caption=sonn1;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::FormKeyPress(TObject *Sender, char &Key)
{
if(Key=='1')
Button5->Click();
if(Key=='2')
Button6->Click();
if(Key=='3')
Button7->Click();
if(Key=='4')
Button9->Click();
if(Key=='5')
Button10->Click();
if(Key=='6')
Button11->Click();
if(Key=='7')
Button13->Click();
if(Key=='8')
Button14->Click();
if(Key=='9')
Button15->Click();
if(Key=='/')
Button24->Click();
if(Key=='+')
Button18->Click();
if(Key=='-')
Button17->Click();
if(Key=='*')
Button19->Click();
if(Key=='^')
Button25->Click();
if(Key=='%')
Button12->Click();
if(Key=='c'||Key=='C')
Button23->Click();
if(Key=='.')
Button1->Click();
if(Key=='=')
Button3->Click();
}
//---------------------------------------------------------------------------


void __fastcall TForm1::XClick(TObject *Sender)
{
Panel1->Visible=true;
Panel3->Visible=false;
}
//---------------------------------------------------------------------------

void __fastcall TForm1::M1Click(TObject *Sender)
{
Panel1->Visible=false;
Panel3->Visible=true;
}
//---------------------------------------------------------------------------

