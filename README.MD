### replaced by javascript

<!-- function presentAlert() {
  const alert = document.createElement('ion-alert');
  alert.cssClass = 'my-custom-class';
  alert.header = 'Alert';
  alert.subHeader = 'Subtitle';
  alert.message = 'This is an alert message.';
  alert.buttons = ['OK'];

  document.body.appendChild(alert);
  return alert.present();
} -->
### another for fuction simple  angular
<!-- 
 alertCtrl.create({
          message:'Please enter valid reason and amount!',
          header:'Invalid inputs',
          buttons:['Okay']
        })
           .then(alertElement => {
            alertElement.present()
        }) -->

<!-- 
        presentAlert() {
    const alert = await this.alertController.create({
      cssClass: 'my-custom-class',
      header: 'Alert',
      subHeader: 'Subtitle',
      message: 'This is an alert message.',
      buttons: ['OK']
    });

    await alert.present();
  } -->