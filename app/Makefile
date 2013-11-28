
test:
	@./node_modules/.bin/mocha ./test/

		 
.PHONY: test


define publishzip
  mkdir -p ../Builds/
  rm -rf ../Builds/app.zip
  zip -x \*node_modules\* -r ../Builds/app.zip .
endef

publish:
	@$(call publishzip)

