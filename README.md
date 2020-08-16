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
.form 
.modal-form 
.form-title 
.form-input 
.modal-form-list 
.modal-form-list:not(:last-child)
.modal-form-list:last-child 
.modal-form-list input 
}
.modal-form-list textarea 
.form-label 
.modal-form-list
.form-svg 
.form-svg 
.label-comment 
.form-label 
.input-modal 
.form-accept 
.form-mark
.form-mark-text 
.btn-form 
.btn-close 
.close-svg 
.modal-form-list:hover .form-svg 
.modal-form-list:hover input,
.modal-form-list:hover textarea 
.textarea-comment 
.modal-form-list:hover label


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

