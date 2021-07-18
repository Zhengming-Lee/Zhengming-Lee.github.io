---
layout: post
title: Banking Theory I
---


1. Industrial Organization of Banking 
   1. Model of perfect competition
   2. Models of market power
      1. Local monopoly banks (Klein-Monti Model)
      2. Cournot competition
      3. Bertrand competition
      4. Monopolistic competition (Salop model)
2. Bank Profitability 
3. Market Power, Capital Regulation, and Bank Risk-Taking
4. Banks and the Transmission of Monetary Policy
5. The Risk-Taking Channel of Monetary Policy
6. Regulation of the Basel Committe

# Banks' balance sheet
Asset|Liability
--:|--:
Loans($l$) | Deposits($d$)
Required Reserves ($\phi d$) | Equity Capital ($k$)

# Model of perfect comeptition
1. model setup
   1. large number of identical banks compete for deposits and loans
   2. perfect competition with deposit rate $r_D$  and loan rate $r_L$  taken as given
   3. market supply of deposits $D(r_D)$   
   4. market demand for loans $L(r_L)$ 
   5. interbank market where banks can borrow or lend at rate r which is set by central bank 
2. Assumptions
   1. bank loans are riskless, no default
   2. banks have no equity capital
   3. no intermediation costs
3. **Benchmark**
   1. Bank balance sheet: $l = d+b$ 
   2. Bank profits:  $$\pi=lr_L-dr_D-br=\underbrace{l(r_L-r)}\_{profits\ from\ lending}+\underbrace{d(r-r_D)}\_{profits\ from\ deposit\ taking}$$
   3. Competitive equilibrium characterized by zero-profit conditions: $$r_L=r\ and\ r_D=r$$
   4. Equilibrium deposits: $$ D(r_D) = D(r)  $$
   5. Equilibrium loans: $$ L(r_L) = L(r)  $$
4. **Reserve requirements $\phi$**
   1. **Bank balance sheet**: $$l +\phi d=d+b  $$
   2. Bank profits: $$ \pi=lr_L-dr_D-br +\phi d\bar{r}=\underbrace{ l(r_L-r)}\_{profits\ from\ lending}+\underbrace{d[(1-\phi)r+\phi\bar{r}-r_D]}\_{profits\ from\ deposits\ taking} $$
   3. Non-remunerated ( $\bar{r}=0 $): $$r_L=r\ and\ r_D=(1-\phi)r $$
   4. Remunerated at the rate $\bar{r}<r$ : $$r_L=r\ and\ r_D=(1-\phi)r+\phi \bar{r} $$
   5. Renumerated at the rate $\bar{r}=r$: $$r_L=r\ and\ r_D=r $$
5. **Capital requirements $\gamma$**
   1. **Bank balance sheet**: $$l=d+b+k=d+b+\gamma l $$
   2. Shareholders requirement premium $\delta>0$ on equity
   3. Bank profits: $$ \pi=lr_L-dr_D-br -\gamma l(r+\delta)=\underbrace{ l[r_L-(r+\gamma \delta)]}\_{profits\ from\ lending}+\underbrace{d(r-r_D)}\_{profits\ from\ deposits\ taking} $$
   4. Competitive equilibrium: $$  r_L=r+\gamma\delta\ and\ r_D=r $$
   5. **Fixed supply of capital $K$** : 
      1. $\delta$   is determined by $\gamma L(r+\gamma\delta)=K $
      2. bank lending is given by $L = K/\gamma$ , independent of policy rate $r$ 
6. **Intermediation costs $c(d,l)$**
   1. Bank balance sheet: $$ l=d+b$$ 
   2. Bank profits:$$ \pi = lr_L-dr_D-br-c(d,l) = l(r_L-r)+d(r-r_D)-c(d,l) $$
   3. Competitive equilibrium: $$ r_L-r=\frac{\partial c(d,l)}{\partial l}\ and\ r-r_D = \frac{\partial c(d,l)}{\partial d}\ $$
7. Interbank market freezes 

# Market Power
1. Bank balance sheet: $$ l=d+b $$
2. Local monopoly banks: $$ \max_{r_L,r_D}[L(r_L)(r_L-r)+D(r_D)(r-r_D)]\to\\ FOC: \ \frac{r_L-r}{r_L}=\frac{1}{\epsilon_L}\ and\ \frac{r-r_D}{r_D}=\frac{1}{\epsilon_D} $$
3. Cournot competition (work with inverse supply of deposits r_D(D) and inverse demand for loans r_L(L) : $$ \max_{d_j,l_j}[l_j(r_L(l_j+\sum_{i\neq j}l_i)-r)+d_j(r-r_D(d_j+\sum_{i\neq j}d_i))]\to \\  FOC:\ r_L(L)-r+l_jr_L^{\prime}(L)=0\ and\ r-r_D(D)-d_jr_D^{\prime}(D)=0\\ Symmetric\ eq.:\ r_L(L)-r = \frac{Lr_L^{\prime}(L)}{n}\ and\ r-r_D(D)= \frac{Dr_D^{\prime}(D)}{n} $$
4. Cournot competition with no interbank market
5. Bertrand competition (work with supply of deposits $D(r_D)$ and demand for loans $L(r_L)$ ): $$ r_L =r\ and\ r_D = r $$
6. Monopolistic competition (Circular road model/Salop model): Competition in deposit market where banks invest in an asset that pays an exogenous return $r$, depositors travelling to bank (located on circumference of unit length) involves *travel cost*  $\mu$ per unit of distance.$$ Intermediation\ margin:\ r-r_D = \frac{\mu}{n}\\ Equilibrium\ bank\ profits:\ \pi(n)=\frac{1}{n}(r-r_D)=\frac{\mu}{n^2} $$

# Bank Profitability
1. Cournot competition for loans and deposits among n banks
2. Linear inverse demand for loans $$ r_L(L)=a-bL $$
3. Linear inverse supply of deposits $$ r_D(D) = c+eD $$ 
4. Interbank market where banks borrow and lend at $r$
5. Fixed amount k of equity capital per bank
6. Bank $j$ balance sheet $$l_j=d_j+b_j+k$$
7. Bank $j$ profits $$ \pi_j = l_jr_L-d_jr_D-b_jr=\underbrace{l_j(r_L-r)}\_{profits from lending}+\underbrace{d_j(r-r_D)}\_{profits from deposit taking}+kr $$
8. Loan market equilibrium $$\max_{l_j}[(a-bL-r)l_j]\\ FOC:\ a-bL-r-bl_j=0\\ symmetric\ eq.:\ L=\frac{n}{n+1}\frac{a-r}{b}\ and\ r_L=\frac{a+nr}{1+n}\\ Loan\ market\ margin:\ r_L-r= \frac{a-r}{1+n}\\ Profts\ from\ lending:\ \pi_L=(r_L-r)\frac{L}{n}\\ r \uparrow \to  \pi_L \downarrow\ and\ n \uparrow \to \pi_L \downarrow  $$

9. Deposit market equilibrium $$ deposit\ market\ margin:\ r-r_D=\frac{r-c}{1+n}$$ $$ profits\ from\ deposit\ taking:\ \pi_D=(r-r_D)\frac{D}{n}\\ r \uparrow \to  \pi_D \uparrow\ and\ n \uparrow \to \pi_D \downarrow 
 \\ r \downarrow \\ \Rightarrow r_L \downarrow, r_D \downarrow\\ \Rightarrow r_L-r \uparrow, r-r_D \downarrow \\ \Rightarrow \pi_L \uparrow, \pi_D \downarrow \\ \Rightarrow \pi = \pi_L+\pi_D+kr ?  $$

10. Return on Equity (ROE) $$ROE = \frac{\pi}{k} = \frac{\pi_L+\pi_D}{k}+r  $$

11. Market value of bank and price-to-book ratio
$$ \nu = \frac{\pi+k}{1+r+\delta}=\frac{1+ROE}{1+r+\delta}k\\  \frac{\nu}{k}=\frac{1+ROE}{1+r+\delta}  \\  \nu = \pi(\frac{1}{1+r+\delta}+\frac{1}{(1+r+\delta)^2}+...)=\frac{\pi}{r+\delta} = \frac{ROE}{r+\delta} k\\ \frac{\nu}{k} = \frac{ROE}{r+\delta} $$

12. Introducing capital requirement $k_j \geq \gamma l_j$  : two possible cases if the constraint is binding
   1. banks choose not to raise equity $\to L=nk/\gamma $
   2. banks choose to raise equity, in which case initial shareholders have to pay new shareholders $\delta(\gamma l_j-k) $
   3. Loan market equilibrium $$ max_{l_j} [(a-bL-r)l_j - \delta max \\{\gamma l_j-k,0\\}] $$


# Reference
1. https://www.cemfi.es/~repullo/
2. https://www.cemfi.es/~repullo/
3. https://www.aeaweb.org/articles?id=10.1257/mac.4.2.184
