# SMS-Send-Nexmo
สวัสดีครับวันนี้ผมได้ลองทดสอบเขียนสคริปต์ขึ้นมาเพื่อทดสอบการส่ง SMS ของเว็บ Nexmo หวังว่าเพื่อนๆคงใช้ประโยชน์กันนะครับ
สำหรับเพื่อนๆที่ไม่มี Key กันให้ไปสมัครที่เว็บ nexmo.com เพื่อเอา Key กับ Key secret มาใส่ในเเต่ละ TXT ครับ
มันจะให้มา 2 ดอลหรือยูโรผมไม่เเน่ใจ จะกินค่าส่งข้อความละ 0.02 
เวลาใส่เบอร์ไม่ต้องใส่ 0 นะครับ ให้ใส่เป็นรหัสประเทศเเทนเช่น รหัสประเทศไทย12345678 หรือ (66)12345678 เเต่ต้องใส่เเบบนี้นะครับ 6612345678 
สามารถส่งข้อความถี่ๆได้ครับผมตั้งไว้ให้เเล้ว เเค่ใส่จำนวนที่ต้องการเลยครับ

สามารถเเกะสคริปต์ไปศึกษาได้เลยครับเพราะผมก็เขียนไม่ชำนาญยังไม่กระชับเท่าที่ควร

#ใช้เวลาในการสร้างสคริปต์ทั้งสิ้น 2 ชม
#ตัวสคริปต์มีไว้ใช้งานเเบบ Pentest นะครับไม่ได้มีไว้สำหรับโจมตีผู้อื่น หากใช้เพื่อโจมตีผู้อื่นผมขอไม่เกี่ยวข้องใดๆ

git clone https://github.com/apiwat59/SMS-Send-Nexmo   ---------------------------------------------------------                          
chmod +x SMS-Send-Nexmo  ---------------------------------------------------------------------------------------                           cd SMS-Send-Nexmo       ----------------------------------------------------------------------------------------                            ./installer-sendmessage.sh    ----------------------------------------------------------------------------------
./SendMessage.sh   ---------------------------------------------------------------------------------------------
ใส่เบอร์เช่น: 6612345678                                                                                          
หัวข้อความ: ชื่อคนส่ง                                                                                           
ข้อความ: ข้อความอะไรเช่น kuy                                                                                            
จำนวนที่ส่ง: สูงสุด 100 ต่อบัญชี                                                                          

ให้ไปสมัครบัญชีที่เว็บ Nexmo ก่อนครับเพื่อเอา Api Key เเละ Secret มาใส่ตรง api_key.txt เเละ api_secret.txt
