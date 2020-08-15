# goit-markup-hw-07

<batom>Все</batom>
<batom>Веб-сайты</batom>
<batom>Приложения</batom>
<batom>Дизайн</batom>
<batom>Маркетинг</batom>

Raleway Bold
Roboto Medium
Roboto Regular
Roboto Bold
Roboto Black

<!--виписуємо класи по секціях--> 

<!--Загальні класи для всіх-->
link 
active
list
button 
text
second-title
img 

<!--navigation-->
navigation 
header-logo 
logo-web 
navigation-list 
navigation-list-item 
navigation-line-studio ? для псевдокласу after 
navigation-list-link 
<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->  
.navigation-line-studio::after

address-util 
address
address-list
address-item
address-emaile
address-emaile-svg 
address-item
address-tel
address-tel-svg 



<!--заголовок і кнопка-->
decorative-img 
container-h1
maine-taitle
text-butto

<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   




<!--Наші Стандарти-->
standards 
list-standards
standards-list-item
standards-br-svg 
standards-list-item-svg
satandards-items
text
<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   



<!--Чем мы занимаемся--> 
projects 
second-title 
effect-studio-list-img
list-img
studio-effect-text-div
img
projects-satandards-items 
studio-effect-text

<!--Наша команда--> 
our-team-section 
our-team 
second-title
our-team-list 
manager 
our-team-list-container 
manager-name
profesion
social-list
social-list-item
solcial-link-item
solcial-icon-svg

<!--Постоянные клиенты--> 
regular-customers
second-title
regular-customers-list 
regular-customers-list-item4
regular-customers-dr
regular-customers-svg

<!--Footer: Лого, Адреса, Приєднуйтесь, Підписуйтесь--> 
<!--<div class="footer-container">--> 
footer-div-container 
footer-div-address
footer-logo logo
logo-web
list
footer-adres
address-emaile-foote
address-emaile
address-tel 
join-social-link 
action 
social-list 
vidstan-icon-footer 
social-list-item 
solcial-link-item
footer-icon-link 
solcial-icon-svg

sign-up 
action 
imput-footer
imput
footer-actions-input-text-emaile 
footter-button
olcial-icon-svg
plane-icon-send 

<!--portfolio-->
<!--Портфоліо Кнопки навігації (ВСЕ,ВЕБ_САЙТ,Додатки,Дизайн,Маркетинг)-->
div-portfolio-sectio
portfolio-button
portfolio-list-btn
portfolio-list-item-btn
button-portfolio
<!--Портфоліо Список: (ВСЕ,ВЕБ_САЙТ,Додатки,Дизайн,Маркетинг) -->
portfolio-div 
portfolio-list-works
portfolio-works-item
portfolio-focus-item 
portfolio-list-title 
portfolio-text 

effect-item-div - то ефекти !!!!
effect-div - то ефекти !!!!
text portfolio-effect-text - то ефекти !!!! 

<!--Декоративні ефекти + Векторна графіка - доставляю, розкидаю по секціях то що залишилось по відповідно до класу який є в тій чи іншій секції  -->   
navigation-line-portfolio::after






<!--Модалье вікно--> 
text portfolio-effect-text

/*Модальне вікно*/
.form {
  position: fixed;
  left: 0;
  top: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  background-color: rgba(0, 0, 0, 0.2);
  z-index: 100;
}
.modal-form {
  position: relative;
  padding: 40px;
  width: 528px;
  height: 581px;
  background: #FFFFFF;
  box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.12), 
  0px 1px 1px rgba(0, 0, 0, 0.14), 
  0px 2px 1px rgba(0, 0, 0, 0.2);
  border-radius: 4px;
  display: flex;
  flex-direction: column;
  align-items: center; 
  animation-name: modal-form-animation;
  }
.form-title {
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 20px;
  line-height: 23px;
  text-align: center;
  letter-spacing: 0.03em;
  color: #212121;
  margin-bottom: 30px;
} 
.form-input {
padding-left: 41px;
}
.modal-form-list {
  width: 448px; 
}
.modal-form-list:not(:last-child) {
  margin-bottom: 28px;
}
.modal-form-list:last-child {
  margin-bottom: 20px;
}
.modal-form-list input {
  height: 40px;
}
.modal-form-list textarea {
  height: 120px;
}
.form-label {
  position: absolute;
  top: 12px;
  left: 42px;
  transition: 250ms linear;
}
.modal-form-list {
  position: relative;
}
.form-svg {
  position: absolute;
  top: 12px;
  left: 19px;
  fill: #212121;
  transition: 250ms linear;
}
.form-svg {
  transition: 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.label-comment {
  position: absolute;
  top: 12px;
  left: 16px;
  transition: 250ms linear;
}
.form-label {
  position: absolute;
  top: 12px;
  left: 42px;
  transition: 250ms linear;
}

.input-modal {
  width: 100%;
  margin-right: auto;
  margin-left: auto;
}
.form-accept {
  display: flex;
  align-items: center;
  display: flex;
  text-align: center;
  justify-content: center;
  margin-bottom: 20px;
}
.form-mark {
  margin-right: 8px;
}
.form-mark-text {
  font-family: Roboto;
  font-style: normal;
  font-weight: normal;
  font-size: 14px;
  line-height: 1.71;
  letter-spacing: 0.03em;
  color: #757575;
}
.btn-form {
  padding: 10px 55px;
  background: #2196F3;
  box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15);
  border-radius: 4px;
  font-family: Roboto;
  font-style: normal;
  font-weight: bold;
  font-size: 16px;
  line-height: 30px;
  display: flex;
  align-items: center;
  text-align: center;
  letter-spacing: 0.06em;
  margin-right: auto;
  margin-left: auto;
  color: #FFFFFF;
  cursor: pointer;

}
.btn-close {
  display: flex;
  position: absolute;
  height: 30px;
  width: 30px;
  top: 14px;
  right: 14px;
  border-color: #000000;
  background: #FFFFFF;
  border: 1px solid rgba(0, 0, 0, 0.1);
  box-sizing: border-box;
  border-radius: 50px;
  justify-content: center;
  align-items: center;
  cursor: pointer;
  transition: 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-close:hover .close-svg,
.btn-close:focus .close-svg {
  fill: #2196F3;
  transition: 250ms linear;
}
.close-svg {
  background-size: contain;
}
.modal-form-list:hover .form-svg {
  fill:  #2196F3;
  box-sizing: 12px;
}
.modal-form-list:hover input,
.modal-form-list:hover textarea {
  border-color: #2196F3;
}
.textarea-comment {
  padding: 15px;
}
.modal-form-list:hover label {
  color: #2196F3;
  top: -20px;
  left: 16px;
}


.form-input:focus + .form-label,
.textarea-comment:focus + .label-comment,
.form-input:not(:placeholder-shown) + .form-label,
.textarea-comment:not(:placeholder-shown) + .label-comment {
  color: #2196F3;
  top: -20px;
  left: 16px;
  box-sizing: 12px;
}
.form-input:focus ~ .form-svg {
  fill:  #2196F3;
}
.is-hidden {
  top: 200px;
  visibility: hidden;
  opacity: 0;
  pointer-events: none;
  transition: 250ms cubic-bezier(0.4, 0, 0.2, 1);
}

