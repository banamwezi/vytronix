# VYTRONIX-
Site VYTRONIX
/* Bouton WhatsApp flottant */
.whatsapp-float {
  position: fixed;
  right: 20px;
  bottom: 20px;
  z-index: 999;
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 14px 20px;
  border-radius: 50px;
  background: #25D366;
  color: #07110a;
  font-weight: 700;
  font-size: 15px;
  box-shadow: 0 8px 30px rgba(37, 211, 102, .30);
  transition: transform .25s, box-shadow .25s;
}

.whatsapp-float:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 35px rgba(37, 211, 102, .45);
}

.whatsapp-float .wa-icon {
  font-size: 23px;
}

@media (max-width: 560px) {
  .whatsapp-float {
    right: 14px;
    bottom: 14px;
    padding: 13px 17px;
    font-size: 14px;
  }
}
