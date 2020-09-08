package com.gp.patterns.ioc;

import org.springframework.beans.factory.annotation.Autowired;
import org.springframework.stereotype.Component;
@Component
public class CustomerImpl implements Customer {

	//CreditCard creditCard= new CreditCardImpl();
	
	
	//field level injection
	//@Autowired
	CreditCard creditCard;
	
	
	//constuctor injection
	@Autowired
	public CustomerImpl(CreditCard creditCard) {
		// TODO Auto-generated constructor stub
		this.creditCard=creditCard;
	}
	
	
	@Override
	public void pay() {
		// TODO Auto-generated method stub
		creditCard.makePayment();

	}


	/*
	 * public CreditCard getCreditCard() { return creditCard; }
	 * 
	 * //setter level injection //@Autowired public void setCreditCard(CreditCard
	 * creditCard) { this.creditCard = creditCard; }
	 */

}
