TARGET = libgsi.so

SRCS = libgsi.cpp

HEADERS = 

EXTRALIBS = -lglobus_gss_assist$(GSI_INSTALL_TYPE2) \
	    -lglobus_gssapi_gsi$(GSI_INSTALL_TYPE2) \
            -lglobus_gsi_credential$(GSI_INSTALL_TYPE2) \
            -lglobus_gsi_proxy_core$(GSI_INSTALL_TYPE2) \
	    -lglobus_gsi_callback$(GSI_INSTALL_TYPE2) \
	    -lglobus_oldgaa$(GSI_INSTALL_TYPE2) \
	    -lglobus_gsi_sysconfig$(GSI_INSTALL_TYPE2) \
	    -lglobus_gsi_cert_utils$(GSI_INSTALL_TYPE2) \
	    -lglobus_openssl_error$(GSI_INSTALL_TYPE2) \
	    -lglobus_openssl$(GSI_INSTALL_TYPE2) \
	    -lglobus_proxy_ssl$(GSI_INSTALL_TYPE2) \
            -lssl \
            -lcrypto \
	    -lglobus_common$(GSI_INSTALL_TYPE2) \
	    -lglobus_callout$(GSI_INSTALL_TYPE2) \
	    -L/usr/lib/irods/externals \
	    -lboost_chrono -lboost_date_time -lboost_filesystem \
	    -lboost_iostreams -lboost_program_options -lboost_regex \
	    -lboost_system -lboost_thread \
	    -lltdl$(GSI_INSTALL_TYPE2) \
		/usr/lib/libirods_client_api_table.a \
                /usr/lib/libirods_client_plugins.a



include ../Makefile.base
