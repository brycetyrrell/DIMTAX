case
when
  (org_type = 'Business' and term_desc ilike '%property%') or
  (term_desc ilike '%Business%' and term_desc ilike '%property%') or
  (term_desc ilike '%Business%' and term_desc ilike '%Mortgage%')
then '8616332 BUSINESS REAL ESTATE LOAN'
when
  (org_type = 'Business' and term_desc ilike '%track dev%') or
  (org_type = 'Business' and term_desc ilike '%CONSTRUCTION%') or
  (org_type = 'Business' and term_desc ilike '%development%')
then '50021697 BUSINESS CONSTRUCTION AND DEV'
when
  (org_type = 'Business' and term_desc ilike '%sba%' and term_desc ilike '%loan%') or
  (org_type = 'Business' and term_desc ilike '%small Business%' and term_desc ilike '%loan%')
then '35095020 BUSINESS SBA LOANS'
when
  (org_type = 'Business' and term_desc ilike '%sba%' and term_desc ilike '%line%') or
  (org_type = 'Business' and term_desc ilike '%small Business%' and term_desc ilike '%line%') or
  (org_type = 'Business' and term_desc ilike '%sba%' and term_desc ilike '%loc%') or
  (org_type = 'Business' and term_desc ilike '%small Business%' and term_desc ilike '%loc%')
then '47667125 BUSINESS SBA LINE OF CREDIT'
when
  (org_type = 'Business' and term_desc ilike '%unsecure%' and term_desc ilike '%loan%')
then '35095018 BUSINESS UNSECURED LOAN'
when
  (org_type = 'Business' and term_desc ilike '%secure%' and term_desc ilike '%loan%')
then '35095017 BUSINESS SECURED LOAN'
when
  (org_type = 'Business' and term_desc ilike '%unsecure%' and term_desc ilike '%line%') or
  (org_type = 'Business' and term_desc ilike '%unsecure%' and term_desc ilike '%loc%')
then '35094991 BUSINESS UNSECURED LINES OF CREDIT'
when
  (org_type = 'Business' and term_desc ilike '%secure%' and term_desc ilike '%line%') or
  (org_type = 'Business' and term_desc ilike '%secure%' and term_desc ilike '%loc%')
then '35094990 BUSINESS SECURED LINES OF CREDIT'
when
  (org_type = 'Business' and term_desc ilike '%roth%') or
  (term_desc ilike '%Business%' and term_desc ilike '%roth%') or
  (org_type = 'Business' and term_desc ilike '%ira%') or
  (term_desc ilike '%Business%' and term_desc ilike '%ira%') or
  (org_type = 'Business' and term_desc ilike '%invest%') or
  (term_desc ilike '%Business%' and term_desc ilike '%invest%') or
  (org_type = 'Business' and term_desc ilike '%retire%') or
  (term_desc ilike '%Business%' and term_desc ilike '%retire%')
then '35095009 BUSINESS INVESTMENT ACCOUNT'
when
  (term_desc ilike '%Business%' and term_desc ilike '%money market%') or
  (org_type = 'Business' and term_desc ilike '%money market%') or
  (term_desc ilike '%Business%' and term_desc ilike '%moneymarket%') or
  (org_type = 'Business' and term_desc ilike '%moneymarket%')
then '12631947 BUSINESS MONEY MARKET'
when
  (org_type = 'Business' and term_desc ilike '%cd%') or
  (org_type = 'Business' and prod_type = 'CD') or
  (term_desc ilike '%Business%' and term_desc ilike '%cd%')
then '8616331 BUSINESS CERTIFICATES OF DEPOSIT'
when
  (org_type = 'Business' and prod_type = 'Savings') or
  (term_desc ilike '%Business%' and term_desc ilike '%saving%') or
  (term_desc ilike '%municipal%' and term_desc ilike '%saving%') or
  (term_desc ilike '%non-profit%' and term_desc ilike '%saving%') or
  (term_desc ilike '%IOLTA%')
then '8616330 BUSINESS SAVINGS ACCOUNTS'
when
  (org_type = 'Consumer' and term_desc ilike '%roth%') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%roth%')
Then '35095016 CONSUMER ROTH IRA'
when
  (org_type = 'Consumer' and term_desc ilike '%ira%') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%ira%')
then '35095015 CONSUMER TRADITIONAL IRA'
when
  (org_type = 'Consumer' and term_desc ilike '%invest%') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%invest%') or
  (org_type = 'Consumer' and term_desc ilike '%retire%') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%retire%') or
  (org_type = 'Consumer' and term_desc ilike '%SEP%') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%SEP%')
then '35095025 CONSUMER OTHER INVESTMENT ACCOUNT'
when
  (org_type = 'Consumer' and term_desc ilike '%Home Equity loan%') or
  (org_type = 'Consumer' and term_desc ilike '%helon%') or
  (org_type = 'Both' and term_desc ilike '%Home Equity loan%') or
  (org_type = 'Both' and term_desc ilike '%helon%') or
  (org_type = 'Consumer' and term_desc ilike '%Equity loan%') or
  (org_type = 'Both' and term_desc ilike '%Equity loan%') or
  (org_type = 'Consumer' and term_desc ilike '%second Mortgage%') or
  (org_type = 'Both' and term_desc ilike '%second Mortgage%')
then '35094998 CONSUMER HOME EQUITY LOAN'
when
  (org_type = 'Consumer' and term_desc ilike '%Home Equity line%') or
  (org_type = 'Consumer' and term_desc ilike '%heloc%') or
  (org_type = 'Both' and term_desc ilike '%Home Equity line%') or
  (org_type = 'Both' and term_desc ilike '%heloc%')
then '35094997 CONSUMER HOME EQUITY LINE'
when
  (org_type = 'Consumer' and term_desc ilike '%Property%') or
  (org_type = 'Both' and term_desc ilike '%Property%') or
  (org_type = 'Consumer' and prod_type = 'Mortgage') or
  (org_type = 'Both' and prod_type = 'Mortgage') or
  (term_desc ilike '%Consumer%' and term_desc ilike '%Property%')
then '8616201 CONSUMER MORTGAGE LOAN'
when
  (org_type = 'Consumer' and term_desc ilike '%unsecure%' and term_desc ilike '%loan%') or
  (org_type = 'Both' and term_desc ilike '%unsecure%' and term_desc ilike '%loan%')
then '35095024	CONSUMER UNSECURED LOAN'
when
  (org_type = 'Consumer' and term_desc ilike '%secure%' and term_desc ilike '%loan%') or
  (org_type = 'Both' and term_desc ilike '%secure%' and term_desc ilike '%loan%')
then '35095023	CONSUMER OTHER SECURED LOAN'
when
  (org_type = 'Consumer' and term_desc ilike '%unsecure%' and term_desc ilike '%line%') or
  (org_type = 'Consumer' and term_desc ilike '%unsecure%' and term_desc ilike '%loc%') or
  (org_type = 'Both' and term_desc ilike '%unsecure%' and term_desc ilike '%line%') or
  (org_type = 'Both' and term_desc ilike '%unsecure%' and term_desc ilike '%loc%')
then '35094977	CONSUMER PERSONAL UNSECURED LINES'
when
   (org_type = 'Consumer' and term_desc ilike '%secure%' and term_desc ilike '%line%') or
   (org_type = 'Consumer' and term_desc ilike '%secure%' and term_desc ilike '%loc%') or
   (org_type = 'Both' and term_desc ilike '%secure%' and term_desc ilike '%line%') or
   (org_type = 'Both' and term_desc ilike '%secure%' and term_desc ilike '%loc%')
then '35094978	CONSUMER PERSONAL SECURED LINES'
end as parent
