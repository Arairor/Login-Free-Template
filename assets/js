// Show / Hidden Input

const showHidenInput = (inputOverLay, inputPass, inputIcon)=>{
    const overlay = document.getElementById(inputOverLay),
          input = document.getElementById(inputPass),
          iconEye = document.getElementById(inputIcon);

    iconEye.addEventListener('click', () =>{
        //change password to text
        if(input.type === 'password'){
            //Switch to text
            input.type = 'text'
            // Change icon
            iconEye.classList.add('bx-show')
        }else{
            //Switch to text
            input.type = 'password'
            // Change icon
            iconEye.classList.remove('bx-show')
        }

        //Toggle the overlay
        overlay.classList.toggle('overlay-content')
    })
}

showHidenInput('input-overlay','input-pass','input-btn-hide')
