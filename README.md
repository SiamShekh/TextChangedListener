Main code:

        editTextText.addTextChangedListener(new TextWatcher() {
            @Override
            public void beforeTextChanged(CharSequence s, int start, int count, int after) {

            }

            @Override
            public void onTextChanged(CharSequence s, int start, int before, int count) {

            }

            @Override
            public void afterTextChanged(Editable s) {
                if (s.toString().equals("SiamShekh")){
                    hello.setVisibility(View.VISIBLE);
                }else {
                    hello.setVisibility(View.GONE);
                }
            }
        });
