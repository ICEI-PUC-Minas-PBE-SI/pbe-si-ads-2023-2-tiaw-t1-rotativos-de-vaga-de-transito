# Código do Projeto

#boxReservas{
   margin: auto;
   margin-top: 50px;
   margin-bottom: 50px;
    display: flex;
    min-height: 500px;
    height: auto;
    width: 90%;
    padding: 0;
    flex-wrap: wrap;
    box-shadow: rgba(14, 30, 37, 0.12) 0px 2px 4px 0px, rgba(14, 30, 37, 0.32) 0px 2px 16px 0px;
}




/* CSS */
.vagasBox {
  background-color: #111827;
  border: 1px solid transparent;
  border-radius: .75rem;
  box-sizing: border-box;
  color: #FFFFFF;
  cursor: pointer;
  flex: 0 0 auto;
  font-family: "Inter var",ui-sans-serif,system-ui,-apple-system,system-ui,"Segoe UI",Roboto,"Helvetica Neue",Arial,"Noto Sans",sans-serif,"Apple Color Emoji","Segoe UI Emoji","Segoe UI Symbol","Noto Color Emoji";
  font-size: 1.125rem;
  font-weight: 600;
  line-height: 1.5rem;
  padding: .75rem 1.2rem;
  text-align: center;
  text-decoration: none #6B7280 solid;
  text-decoration-thickness: auto;
  transition-duration: .2s;
  transition-property: background-color,border-color,color,fill,stroke;
  transition-timing-function: cubic-bezier(.4, 0, 0.2, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  width: auto;
}

.vagasBox:hover {
  background-color: #374151;
}

.vagasBox:focus {
  box-shadow: none;
  outline: 2px solid transparent;
  outline-offset: 2px;
}
.vagasBox{
    
    height:80px;
    width: 20%;
    margin:2% 5% 2% 5%;
    box-shadow: rgba(67, 71, 85, 0.27) 0px 0px 0.25em, rgba(90, 125, 188, 0.05) 0px 0.25em 1em;    
}

@media (min-width: 768px) {
  .vagasBox {
    padding: .75rem 1.5rem;
    
  }
}
@media (max-width: 900px) {
    .vagasBox {
      width: 40%;
      margin: auto;
      
      
    }
  }
  #campoParaReservas{
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  #campoParaReservas h2{
    margin-top: 70px;
    font-size: 40px;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }
