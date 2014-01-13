
test:
	@./node_modules/.bin/mocha ./test/

		 
.PHONY: test


define publishzip
	rm -rf ../build/
	rm -rf ../Builds/
  mkdir -p ../build/
  rm -rf ../build/app.zip
  zip -x \*node_modules\* -r ../build/app.zip .
endef

publish:
	@$(call publishzip)

